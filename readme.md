## RUN

```
docker run -d \
  --name phim \
  -e PORT=6969 \
  -e VIRTUAL_HOST=phim.clgt.vn \
  -e SECRET=whatever \
  quocnguyen/phim
```

## Test comamnd

`export PORT=7777; node index.js`