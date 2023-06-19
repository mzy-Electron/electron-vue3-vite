
<h1 align=center>
  Electron + Vue 3 + Vite - Demo
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
使用 Electron Forge 打包和分发应用，在脚本运行后，您应该看到一个 out 文件夹，其中包括可分发文件与一个包含其源码的文件夹。

```
npm run make
```
out/make 文件夹中的应用程序应该可以启动了！   
![image](https://github.com/mzy-ly/my-electron-app/assets/37282073/362305f2-fde5-45de-9b32-17fa07ff5201)

## 安装应用包
### window系统：
这一层的这个带setup的exe执行文件是安装包，发给别人双击就能把我们的软件安装到对方电脑。win-unpacked文件夹，里面有一个electron-vue-basiccc.exe，这是直接运行的执行文件，双击直接运行软件。
![image](https://github.com/mzy-Electron/electron-vue3-vite/assets/37282073/e4f3d6e8-0dcc-4f2b-838b-9543ca4de7ff)

### macOS系统：
可以看到electron_dist下有个.dmg包，双击直接运行软件即可安装
![image](https://github.com/mzy-Electron/electron-vue3-vite/assets/37282073/5501f680-7b84-42a7-b282-bd1f71e387d2)


