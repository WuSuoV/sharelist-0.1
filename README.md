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

## 更新

```bash
bash update.sh
```
