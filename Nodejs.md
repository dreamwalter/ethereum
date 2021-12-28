# Node 升級

1. 利用Node.js的多版本管理器n
```
sudo npm cache clean -f   // 清除nodejs的cache：
sudo npm install -g n     // 使用npm安裝n模塊
npm view node versions    // node所有版本
sudo n latest             // 升級到最新版本
sudo n stable             // 升級到穩定版本
sudo n xx.xx              // 升級到具體版本
```
