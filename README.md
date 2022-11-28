# NodeJS-API-TypeScript-and-Repository-Pattern
Este un proyecto de una API que implementa una arquitectura orientada al uso de repositorios y la facilidad de cambiar de una base de datos a otra a través de la inyección y contenedor de dependencias.

## ¿Cómo levantar el proyecto?
El proyecto esta compuesto por 2 proyectos, el primero es para **gestionar los ingresos y salida de efectivo** de nuestro cliente y el segundo para las **credenciales de acceso**.

Para ambos proyectos deberán instalar los paquetes de npm.

```
npm install
```

Y para levantar el proyecto en modo de desarrollo

```
npm run start:dev
```

## Base de datos
El proyecto hace uso del patrón repositorio y puede intercambiar entre una base de datos y otra. En ambos casos se adjuntan los scripts para SQL Server y MySQL.

El usuario por defecto es:

```
usuario: eduardo@kodoti.com
password: 123456
```