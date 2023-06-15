
<h1 align="center">
  electron-demo
</h1>
<p align="center">
  <a href="https://www.electronjs.org/zh/docs/latest/">Electron 官方文档</a>
</p>


本项目将会通过使用Electron创建一个极简的 Hello World 应用   

## 安装依赖
```
npm install
```

## 启动
app将会自动打开一个浏览器窗口，来展示包含当前正在运行的 Chromium, Node.js与 Electronweb等版本信息的web界面
```
npm run start
或
npm start
```
![3451684403015_ pic](https://github.com/mzy-ly/my-electron-app/assets/37282073/ef4f742d-1cb3-4fc0-95c8-38e1d23ac914)


## 打包
使用 Electron Forge 打包和分发应用，在脚本运行后，您应该看到一个 out 文件夹，其中包括可分发文件与一个包含其源码的文件夹。

```
npm run make
```
out/make 文件夹中的应用程序应该可以启动了！   
![image](https://github.com/mzy-ly/my-electron-app/assets/37282073/362305f2-fde5-45de-9b32-17fa07ff5201)