## Members

Teachers: Ing. Orlando F. Brea y Lorena R. Izzo

Students:

Maza Gabriel /
Camean Fenoy Juan Pablo /
Paak Jorge German / Cammarota Federico /
Casquero Ricardo /
Damiani Juan /

## Install

To start you must have Node.js installed and import the biblioteca.sql file into its respective database.

```
node install
```

For running
```
node start
```
# Api endpoints.

## Api categoria
```
GET     /api/categoria 

POST    /api/categoria 

GET     /api/categoria/:id 

DELETE  /api/categoria/:id 
```
## Api Persona
```
GET     /api/persona 

POST    /api/persona 

GET     /api/persona/:id 

PUT     /api/persona/:id 

DELETE  /api/persona/:id 
```
## Api Libro
```
GET     /api/libro 

POST    /api/libro 

GET     /api/libro/:id 

PUT     /api/libro/:id 

DELETE  /api/libro/:id 

PUT     /api/libro/prestar/:id 

PUT     /api/libro/devolver/:id 
```