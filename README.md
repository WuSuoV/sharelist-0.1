# sharelist-0.1

## 安装

进入项目目录执行：

```bash
npm install
npm install pm2 -g

pm2 start app.js --name sharelist --env prod
pm2 save
pm2 startup
```

或

宝塔的PM2管理器

![image-20221001024601951](https://a-image.1ove.club/image/2022/10/image-20221001024601951.png)

## 更新

```bash
bash update.sh
```
