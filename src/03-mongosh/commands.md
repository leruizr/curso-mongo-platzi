## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://leruizres:0434RUiz1631..@mongodb86.wnoaf.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```