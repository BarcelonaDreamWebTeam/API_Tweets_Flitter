# FLITTER
```sh
Base de datos básica para una aplicación de práctica alusiva a twitter.
```

Para iniciar se ha instalado nodemon el cual permite arrancar la aplicación con un comando sencillo.
Pero que a su vez de le han instalado todas sus dependencias y se ha modificado para que pueda funcionar en cualquier tipo de sistema operativo.
```sh
npm run dev 
```

Para actualizar, mostrar o realizar modificaciones a los datos iniciales de la base de datos, se ha creado el script init-db.js. Se ha creado para inicializar la base de datos con los datos minimos para su fucnionamiento en caso de errores insertados o que los datos sean eliminados por error.

Se inicia con el siguiente comando:
```sh
npm run init-db 
```
# DOCUMENTACION DE LA API

Modelos de llamada de la api

Para mostrar la lista de tweets se ejecuta: 
```sh
http://localhost:3000/api/tweets
```


