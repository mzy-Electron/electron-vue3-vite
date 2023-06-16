
<h1 align=center>
  Electron + Vue 3 + Vite
</h1>

  electron+vite+vue3+electon-builder demo 这个模板应该有助于你开始在Vite和Electron中开发Vue 3。模板使用Vue 3`<script setup>`SFCs，请查看 [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) 和 <a href="https://www.electronjs.org/zh/docs/latest/">Electron docs</a> 来学习更多.   



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

## 安装应用包
### window系统：
这一层的这个带setup的exe执行文件是安装包，发给别人双击就能把我们的软件安装到对方电脑。win-unpacked文件夹，里面有一个electron-vue-basiccc.exe，这是直接运行的执行文件，双击直接运行软件。
![image](https://github.com/mzy-Electron/electron-vue3-vite/assets/37282073/e4f3d6e8-0dcc-4f2b-838b-9543ca4de7ff)

### macOS系统：
可以看到electron_dist下有个.dmg包，双击直接运行软件即可安装
![image](https://github.com/mzy-Electron/electron-vue3-vite/assets/37282073/5501f680-7b84-42a7-b282-bd1f71e387d2)


