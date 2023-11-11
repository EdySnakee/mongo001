# Conectar al contenedor

``` sh
docker-compose exec mongodb bash
```


# Conectar con la terminal de mongo

``` sh
=> en locan
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
=> En la nuve
mongosh "mongodb+srv://admin:admin123@cluster0.nvxqpuj.mongodb.net/"
```

``` sh
show dbs
show collections
```


``` sh
use ("store")
bd.productos.find()
```
