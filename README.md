﻿# Sistema de pagos en Linea (Proyecto software 3)

 Este es un sistema el cual se efectuan pagos de manera automatica, definiendo aquien se le debeo o 
 a que entidad se le debe, definir que tipo de duda es y entre otras opciones

## Empezando
 Estas instrucciones le proporcionarán una copia del proyecto en funcionamiento en su máquina local para fines de desarrollo y prueba. Consulte la implementación para obtener notas sobre cómo implementar el proyecto en un sistema en vivo.

## Prerequisito 
 Se como requicito principal y escencial nocesitamos node.js
https://nodejs.org/es/

## Instalando
 Crear el package.json
 
`npm init`

 Se uso nodemon para poder reiniciar el servidor cadavez que se reinicia el proyecto
 
`npm install nodemon -g`

 Se agregan las dependencias para la creacion de la api-rest
 
`npm add express babel-cli babel-preset-es2015 cosinng mongojs `

## Ejecutando pruebas

 Se accede a la carpeta del test
 
`cd test`

 Se instala la selenium webdriver y cucumbre
 
`npm install selenium-webdriver`
`npm install cucumber`

 Se corre la prueba 
 
`npm test`
