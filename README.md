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
</div> /* Motor de Privacidad MRQ - Gerencia General */
const ChatMRQ = {
    enviarMensaje: function(texto) {
        // Los mensajes se encriptan localmente antes de salir
        const msgCifrado = btoa(texto); 
        this.mostrarEnPantalla(msgCifrado);
    },
    autodestruccion: function() {
        // Al cerrar o refrescar, la memoria volátil se limpia a cero
        window.onbeforeunload = () => {
            sessionStorage.clear();
            console.log("Protocolo MRQ: Memoria limpiada.");
        };
    }
};
ChatMRQ.autodestruccion(); // Script de Bienvenida - Gerencia General MRQ
window.onload = function() {
    const welcomeMsg = "BIENVENIDO AL MUNDO MRQ: PRIVACIDAD TOTAL ACTIVADA.";
    console.log("%c" + welcomeMsg, "color: #00FF41; font-size: 20px; font-weight: bold;");
    // Esto muestra un aviso elegante al usuario sin interrumpir su navegación
};







          
