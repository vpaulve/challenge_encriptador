

Este proyecto de encriptador se está usando como base el Figma brindado por Alura de tal forma que se pueda tomar como referencia para el desarrollo del front-end para el proyecto. El arbol de archivos que contiene este proyecto sería el siguiente:

>imagenes
| logo.png
| muneco.png
v styles
| style.css
index.html
script.js


***Archivo index.html:
Se utilizan dos secciones para ingresar y mostrar los textos:

1) text-area: es la sección donde se ingresará el texto a encriptar
2) mensaje: es la sección en donde se mostrá el texto encriptado escrito inicialmente en la sección "text-area"

Se usaran tres botones:

1) Encriptar: el boton permitirá encriptar el texto ingresado en la sección "text-area" mediante la función btnEncriptar()
2) Desencriptar: el boton permitirá desencriptar el texto mostrado en la sección "mensaje" mediante la función btnDesencriptar() previo copiar de dicho texto a la sección "text-area" mediante el uso de CTRL+C o el boton Copiar
3) Copiar: el botón permitirá copiar el texto mostrado en la sección "mensaje" de tal forma que se evita el uso de CTRL+C y se podrá pegar manualmente en la sección "text-area" mediante el uso de CTRL+V


***Archivo script.js
Dicho archivo tiene toda la lógica de programación mediante diversas funciones que se aplicaran a los textos y botones mencionados en el archivo index.html de tal forma que se pueda lograr el objetivo de realizar la encriptación y desencriptación del texto.

Se tienen las siguientes funciones en dicho archivo:

1) btnEncriptar()
2) encriptar(stringEncriptada)
3) btnDesencriptar()
4) desencriptar(stringDesencriptada)
5) btnCopiar()


**Archivo style.css
Contienen los diferentes estilos para el diseño del archivo index.html de tal forma que pueda darle diferentes características como color de texto, fondo de botones, tipografía, posicionamiento de los diferentes elementos involucrados entre otros.


