
<h1 align=center>
  Electron + Vue 3 + Vite
</h1>
<h2>
  electron+vite+vue3+electon-builder demo
</h2>


这个模板应该有助于你开始在Vite和Electron中开发Vue 3。模板使用Vue 3`<script setup>`SFCs，请查看 [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) 和 <a href="https://www.electronjs.org/zh/docs/latest/">Electron docs</a> 来学习更多.   



## 安装依赖
```
npm install
```

## 启动 electron
app将会自动打开一个浏览器窗口，来展示包含当前正在运行的 Chromium, Node.js与 Electronweb等版本信息的web界面
```
npm run start
```
## 启动 vue3
```
npm run dev
```

## 打包
此项目使用electron-builder工具打包
```
// 单独打包electron，窗口加载的是本地页面 'http://localhost:5173/'
npm run dist

// 同时打包vue和electron，窗口加载的是打包后的 index.html页面
npm run distall
```
![image](https://github.com/mzy-Electron/electron-vue3-vite/assets/37282073/27a7ca85-73da-436b-a117-38085b2a669e)
