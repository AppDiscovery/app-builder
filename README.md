# app-builder

基于webpack的app前端构建器，能够打包出vendor分离的代码包，上传至```central-server```以供使用。

使用方法：

1. git clone
2. npm i
3. 修改 ```package.json``` 中的 ```name```
4. 写代码
5. 运行 ```npm start``` 来测试
6. 修改 ```info.json``` 中的应用显示名、经纬度和半径
7. 指定 ```icon.png``` 为安卓客户端中的图标
8. 运行 ```npm run pack``` 来打包
9. 把打包完成的 ```.tar.gz``` 上传至 ```app-repo-server```
