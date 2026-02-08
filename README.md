# .git-hub-workflows-deploy.ymL name: Despliegue Inmediato Mundo MRQ
on:
  push:
    branches:
      - main  # O la rama que uses (master)

jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout del código
        uses: actions/checkout@v4

      - name: Desplegar en GitHub Pages
        uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./  # Publica todo el contenido del repo
          
