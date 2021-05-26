# Frontend

## Angular 

#### Angular 11 

### instalar los paquetes y la dependencia de angular 

```
npm i 
```

### Correr el Proyecto 

```
ng serve 
```

# Backend

## Spring boot 

#### java 11 

### Configuracion de la base de datos (resources/aplication.properties)

```
spring.datasource.url=jdbc:mysql://[localhost]:[puerto]/[namedatabase]?useUnicode=true&useJDBCCompliantTimezoneShift=true&useLegacyDatetimeCode=false&serverTimezone=UTC
spring.datasource.username=[user]
spring.datasource.password=[password]
spring.jpa.database-platform=org.hibernate.dialect.MySQL5InnoDBDialect
spring.jpa.hibernate.ddl-auto=create-drop //solo es de ejemplo no es necesario
logging.level.org.hibernate.SQL=debug

spring.jackson.time-zone=America/Boise //localicacion
spring.jackson.locale=es_CO
```