

- Crear las tablas con el Script
- Ir a aplicaciones properties y definir la base de datos y el usuario
- Disfrutar
- Quitar los system.out.print()
- Invitar a una ronda.


-> Para acceder a la base datos desde terminal habrá que hacer lo siguiente:
    - mysql -hserver -ugftxx -pgftxx (xx remplazar por vuestro número)
    - Ir a gftxx
    - Copiar y pegar todo el esquema

truncate table actor;
truncate table title;
truncate table director;
truncate table category;
truncate table title_actor;
truncate table title_director;
truncate table title_category;

Dependencia necesaria para el 2nd método rest.
<dependency>            
        <groupId>org.springframework.boot</groupId>            
        <artifactId>spring-boot-starter-data-rest</artifactId>        
</dependency>

