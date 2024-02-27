# Commands MongoDB Shell

## Database
* untuk memilih database yang akan digunakan :
```
~ use dbname
```

* untuk melihat semua database :
```
~ show dbs / show databases
```

* untuk menghapus database :
```
~ db.dropDatabase()
```

* untuk mengambil nama database :
```
~ db.getName()
```

* untuk mengambil host database :
```
~ db.hostInfo()
```

* untuk mengambil versi database :
```
~ db.version()
```

## Collection
* untuk mengambil semua collection :
```
~ db.getCollectionNames()
```

* untuk membuat collection :
```
~ db.createCollection("collectionName")
```

* untuk mengambil info collection :
```
~ db.getCollectionInfos()
```

* untuk mendapatkan objek collection :
```
~ db.collectionName
```

* untuk menghitung objek collection :
```
~ db.collectionName.count()
```

* untuk mengambil objek collection :
```
~ db.collectionName.find()
```

* untuk menghapus collection :
```
~ db.collectionName.drop()
```

* untuk mengambil ukuran collection :
```
~ db.collectionName.size()
```