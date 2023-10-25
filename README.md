# Kikoeru

A Doujin Voice Database

![kikoeru](assets/kikoeru.png)

## Start the server
```bash
docker run -d --name kikoeru -v $(pwd)/data:/data -p 2333:2333 vscodev/kikoeru
```

## Sync voice metadata
```bash
docker exec -it kikoeru sync
```

## Refresh voice metadata
```bash
docker exec -it kikoeru refresh
```
