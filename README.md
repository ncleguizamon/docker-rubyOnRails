# ruby on rails Docker images 

Aplicación de ruby on rails implementada en docker con una base de datos en posgres
seguir la instruciones en [La documentación oficial.](https://docs.docker.com/compose/rails/)
    

- Despligue en modo desarrollo 

 ```
 docker-compose up
docker-compose run web rake db:create

 ```

 Y si te preguntas como creas un modelo un scaffold 
```
 sudo docker-compose run web rails g scaffold item name description 
```
# docker-rubyOnRails
