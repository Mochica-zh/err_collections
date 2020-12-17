我在用npm i 安装依赖项的时候，报了一个‘npm ERR! A complete log of this run can be found in:
npm ERR! 
提示我升级npm，正确解决办法是:

<img src="https://ae06.alicdn.com/kf/H69dc3a1391254af9b613c5f8f26e28d0y.png"/>

1. 执行 npm install npm@latest -g升级到最新版本
2. 删除本地node_modules 依赖包
3. 执行 npm cache clean --force 清理缓存
4. 最后在 npm install 这样就好了