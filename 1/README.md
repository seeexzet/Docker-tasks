To create image run from this folder:
```
docker build . name_image
```

To create container run:
```
docker run -d -p <your_favorite_port>:80 name_image
```

To open new version of hello-page run:
```
curl localhost:<your_favorite_port>/
```