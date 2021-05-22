
# :fire: Desafio :fire: #

Hola, este documento te permitira instalar imagen docker creada con lo cual se dara por cumplido el desafio.

# Paso 1: Descargar imagen docker

El paso 1 es descargar archivo dokerfile publicado en el github en el que esta actualmente.

# Paso 2:Ejecutar archivo dockerfile

El paso 2 es ejecutar el archivo dockerfile, para lo cual sera necesario ingresar a la consola y dirigirse a la ruta en la cual se alojo el archivo dockerfile, posteriormente desde dicha ruta, ejecutar el comando.

        docker build -t ws-desafio .
        
nota: ws-desafio es el nombre de se dara a la imagen, mientras que el . es la ruta actual donde esta el archivo dockerfile, puede validar que este en la ruta correcta con el comando ls, el cual mostrara el archivo.

# Paso 3:Ejecutar contenedor

El paso 3, es ejecutar el comando. 

        docker run -p 80:80 -d ws-desafio 
        
con este comando se iniciara el contenedor con la imagen recientemente descarga, es utiliza el nombre que se asigno a la imagen, el cual puede ser revisado con el comando.

       docker images
       
para validar que el contenedor quedo activo, puede ejecutar el comando.

      docker ps

# Paso 4: Validar pagina web con nombre codificado

El paso 4, que es el ultimo paso es validar la pagina web con el nombre "Oscar Villarroel" correctamente codificado, para lo cual desde un navegador debera ingresar la direccion.

      localhost
      
si se visualiza de forma correcta, significa que el desafio fue completado.


      
