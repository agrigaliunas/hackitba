# Socialnet Panic Button
 "Protege tus redes sociales, facilmente" 

Social Panic Button (SPB) es una app facil de usar para situaciones de emergencia. 
Si perdes o te roban tu telefono celular, o simplemente notas que estas siendo hackeado, SPB te permite, **con solo apretar un boton**, cambiar todas las contraseñas de tus redes sociales. 


## Informacion de compilacion

Version: 0.1 Beta, released April 3, 2022, ITBA - Buenos Aires, Argentina. Modalidad presencial
Github: https://github.com/igruntplay/hackitba
Creators: Gaspar Onesto, Cristian Arean, Leandro Planas.
Equipo: Vodka Juniors

## Redes Compatibles
Trabajamos para constantemente agregar nuevas redes a nuestra app, vea las redes compatibles en segun la version

Prueba de Concepto V0.1: 
Twitter

Produccion, Version 1 (ETA Julio 2022):
Twitter 
Instagram
Linkedin
Facebook
Discord

## Funcionamiento
SPB frente a la orden del usuario, cambiara todas las contraseñas de las redes sociales seleccionadas, solicitando la renovacion de la contraseña en las redes indicadas, escuchando los correos de renovacion de password, y posterior al cambio, grabara internamente la nueva password.

Para configurar su usuario de SPB necesita lo siguiente:
-Nro de Documento de Identidad
-Email de cada red social (sea este 1 para todas las redes o por separado)
-Acceso, a los emails declarados en el punto 1 (usuario y password)
-Configuracion de Huella digital con lector de huellas. 

Una vez descargada la app, debera crear un usuario con su correo y una password de acceso, luego, le pedira ingresar su huella digital, si esto no estuviera disponible, le pedira tomarse una selfie. 

Configurada la app, simplemente tendra disponible el boton de panico, al activarlo se ejecuta el funcionamiento. Para editar las opciones debera presionar lo 3 puntos, en el borde superior de la pantalla. 

En caso, que no disponga de su celular, puede descargarla en cualquier telefono, logearse con docuemento, huella digital o si no estuviera disponible un sensor de huellas, reconocimiento por IA. Ingresado en la APP podra ejecutar el Panic Button. 


# Detalles tecnicos

SPB corre en un servidor, con un web scrapper (selenium) activando la funcionalidad de renovacion de contraseña, una vez clikeada la funcion, escucha el correo electronico de la app y extrae el link de recuperacion, generando una nueva contraseña aleatoria de 8 digitos que guarda en en su poder. 

Dado que el concepto de SPB es una situacion de emergencia, como ser robo en la via publica, o sustraccion o perdida, SPB permite descargar en cualquier telefono la app, logearse usando la tecnologia de lectura de huellas digitales o reconocimiento por IA(V2.0) si no estuviera la huella disponible, y le permitira inmediatamente ejecutar el boton de panico. Luego, con mayor tranquilidad y lejos del peligro podra acceder a esta app, obtener las nuevas claves, y renovar sus contraseñas por las de su preferencia. 

# Roadmap

SBP tiene previstos los siguientes upgrades

```mermaid
graph LR
A[Beta 0.1 Prueba de Concepto Abr 2022]-->B[1.0 Version de produccion ETA: Jul 2022] --> C[2.0 Agregado IA para reconocimiento facial ETA: Mar 2023] 
```
