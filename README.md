MEAN login semicompleto falta: crear trabajadores y logearse

-En mongodb: crear el super usuario del sistema, para registrar a los administradores.
use mean-angular2-registration-login-example;
db.ROOT.insert({correo:"administrador@gmail.com", clave:"kg1808",nombres:"Super usuario", apellidos: "root"});
-con este usuario entrar al login administrador@gmail.com:kg1808 (se puede cambiar en el comando anterior antes de ejecutarlo)

para Iniciar se necesita:
-Para el cliente
npm install 
npm start 
-Para el server
node server.js 


