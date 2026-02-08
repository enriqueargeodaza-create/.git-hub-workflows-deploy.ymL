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
          publish_dir: ./  # Publica todo el contenido del repo git checkout main
git pull origin main
git add .
git commit -m "ACTIVA INTERRUPTOR: MUNDO MRQ FUNCIONAL" git push origin main --force // Configuración de la Base de Datos MRQ
const mrq_database = {
    project: "MUNDO_MRQ",
    status: "ACTIVE",
    users: [],
    
    registerUser: function(name, energy) {
        const newUser = {
            id: Date.now(),
            username: name,
            level: energy,
            timestamp: new Date().toISOString()
        };
        this.users.push(newUser);
        console.log(`Usuario ${name} integrado con éxito.`);
    }
};
<div id="root">
    <h1>BIENVENIDOS AL MUNDO DE LA GENTE MRQ</h1>
    <p>Acceso: LIBRE | Privacidad: TOTALMENTE ENCRIPTADA</p>
    <button onclick="iniciarSesionAnonima()">ENTRAR SIN RASTRO</button>
</div> <div id="root">
    <h1>BIENVENIDOS AL MUNDO DE LA GENTE MRQ</h1>
    <p>Acceso: LIBRE | Privacidad: TOTALMENTE ENCRIPTADA</p>
    <button onclick="iniciarSesionAnonima()">ENTRAR SIN RASTRO</button>
</div>




          
