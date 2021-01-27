# 서버기동
- Client
```vue
yarn build
```
- Server
```vue
yarn start
```

# Docker
```shell
docker build -t vue-portfolio .
docker run -d -p 3000:3000 --name vue-portfolio --restart:always vue-portfolio
```
