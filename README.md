# VulnerabilityAPI
<div align="left">
  <img src="https://img.shields.io/badge/Framework-.NET%206-blue">
  <img src="https://img.shields.io/badge/Database-SQL%20Server-green">
  <img src="https://img.shields.io/badge/Vulnerability-SQL%20injection-yellow">
  <img src="https://img.shields.io/badge/Release-december%202022-black">
</div>
  
## Índice
- [¿Para qué es esta herramienta?](#¿paraque?)
- [Instrucciones](#instrucciones)

## ¿Para qué es esta herramienta?<a name="paraque"></a>
VulnerabilityAPI es un API rest orientada al aprendizaje de las vulnerabilidades que afectan a las aplicaciones web modernas. Cada vulnerabilidad se aloja en un controlador que contiene, por una parte, el desarrollo de una forma insegura, y por otra, soluciones aportadas a dicha vulnerabilad, es decir, el desarrollo de forma segura. Se podrá realizar peticiones a las diferentes partes del código para poder depurar y ver cómo se comporta dicha vulnerabilidad. El proyecto irá creciendo y se irán añadiendo vulnerabiliades nuevas.</br>
Las vulnerabilidades aportadas por el momento son las siguientes:</br>
- SQL injection

## Instrucciones
1. Modificar del archivo appsettings la conexión a la base de datos. En el ejemplo: DESKTOP-7C8R4SU\\SQLEXPRESS
2. Ejecutamos el script que se encuentra en la carpeta Utils, Database.sql
3. Levantamos el API con visual studio y ya estará lista para realizar pruebas

En la siguiente charla, al final de la misma, se realiza una prueba del API con la vulnerabilidad SQL injection.</br>
https://www.youtube.com/watch?v=lQqknAi-nFg
