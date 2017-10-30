## Leanote Docker Image
All data is in /leanote/data volume. We can mount local data folder for this volume.
More details from this [wiki](https://github.com/leanote/leanote/wiki)

#### 1. Create data folder

```
mkdir -p leanote-data/{files,mongodb_backup,public/upload}
```

#### 2. docker-compose up -d



