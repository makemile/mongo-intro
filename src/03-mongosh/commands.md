## Connect to container

```sh
docker-compose exec mongodb
```

## Connect with mongosh

````sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"

```sh
show dbs
show collections
````

```sh
use("platzi store")
db.products.exit()
```
