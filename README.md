# [Trabajo de Fin de Máster - Máster en Ingeniería Web](https://www.linkedin.com/in/andrea-calvo-moreno-63a71b115/)
# Gestión de entrenamientos y reserva para una academia de policía
> Este proyecto consiste en una aplicación web que gestiona los entrenamientos y el sistema de reservas en una 
>academia de policía. El Front-End se desarrolla bajo el framework Angular y el Back-End con Express a partir de Node. Como motor de base 
>de datos se emplea MySQL y la comunicación entre la parte cliente y la servidora se realiza a través de un API Rest.

## Tecnologías necesarias
`TypeScript` `JavaScript` `Node` `Express` `Angular` `MySQL` `GitHub` `GitHub Actions` `Sonarcloud` `Apache` `phpMyAdmin`

## Estado del código
SonarCloud Budges: 
- Front-End with Angular: [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=acalvom_tfm-front-end&metric=alert_status)](https://sonarcloud.io/dashboard?id=acalvom_tfm-front-end)
- Back-End with Express: [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=acalvom_tfm-back-end&metric=alert_status)](https://sonarcloud.io/dashboard?id=acalvom_tfm-back-end)

## :octocat: Repositorios
* [Front-end-angular](https://github.com/acalvom/tfm-front-end)
* [Back-end-express](https://github.com/acalvom/tfm-back-end)

## :gear: Instalación del proyecto
1. Clonar repositorios, **mediante consola**:

   * tfm-front-end
```sh
> cd <folder path>
> git clone https://github.com/acalvom/tfm-front-end
> cd tfm-front-end
tfm-front-end> npm install
```
   * tfm-back-end
```sh
> cd <folder path>
> git clone https://github.com/acalvom/tfm-back-end
> cd tfm-back-end
tfm-back-end> npm install
```

2. Importar el proyecto `tfm-front-end` & `tfm-back-end` mediante **WebStorm** 
   * **Open**, y seleccionar la carpeta del proyecto.

3. Ejecución
    1. BBDD. Arrancar el motor de MySQL y Apache con xampp.
    2. Angular. Ejecutar mediante linea de comando: `> ng serve`
    3. Express. Ejecutar mediante linea de comando: `> nodemon index.js`
