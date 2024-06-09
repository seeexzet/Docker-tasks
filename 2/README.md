To create image run from this folder:
```
docker build . --tag stockproducts
```

To create container run:
```
docker run --name stp -d -p 8000:8000 stockproducts
```

To check request you need to use 'requests-examples.http' file 
or go http://localhost:8000/api/v1/products
 