# Test dev Node React


## Clonar Proyecto Frontend

``` sh
  git clone --recursive git@github.com:AdrianMendez1199/test-dev-node.git
```


## Front End Configuración

 ## Requerimientos
  * nodeJS versión v13.12.0 o superior 
  * yarn versión 1.22.4 o superior
  * git 

  ## Pasos para Configurar Frontend
  ``` sh 
  
    * cd test-dev-node/ticket
    
    * yarn install    
    
    * yarn build 

    * yarn global add serve

  ```

  # Iniciar App
  * serve -s build


 ### Pasos para Configurar Backend

   * create base de datos con script.sql

  ``` sh      
      cd test-dev-node/testReactNodeBackend 
      
      cp src/.env.example .env
      
      cp prisma/.env.example prisma/.env
      
      configurar prisma/.env con credenciales mysql
      
      yarn install    
      
      yarn prisma introspect
      
      yarn prisma generate
  ```

  ### Iniciar Servicio
  * yarn start

  ##### server is runing on http://localhost:4000
 
