# ImitateBaiduPan

该项目是一个使用 Element Plus + VUE3 构建的一个仿新版百度云网盘前端项目。

该项目是 [Naive UI Admin](https://github.com/jekip/naive-ui-admin) 的实践，将 Naive UI Admin 的UI框架修改为 Element Plus，TS修改为JS（[Naive Ui Admin JS](https://github.com/SX-Code/naive-admin-js)），并仿新版百度云盘完成项目。

主要包含下面的功能：
- 文件上传功能：文件切片上传。
- 文件放回收站：文件删除后会进入回收站，可以恢复或者彻底删除。
- 文件预览功能：实现了常见功能的预览，包括：文档文件（docx, pdf, excel）、代码文件、图片文件、视频文件、音频文件。

前端技术：vite vue + axios + pinia + router + js + Element Plus

## 项目预览
[在线预览](http://web.sxcode.rr.nu/mypan/)

### 主页面
![](https://gcore.jsdelivr.net/gh/sx-code/tuchuang@main/mypan/mypan-home.png)
### 图片预览
![](https://gcore.jsdelivr.net/gh/sx-code/tuchuang@main/mypan/mypan-image.png)
### 音频预览
![](https://gcore.jsdelivr.net/gh/sx-code/tuchuang@main/mypan/mypan-music.png)
### 视频预览
![](https://gcore.jsdelivr.net/gh/sx-code/tuchuang@main/mypan/mypan-video.png)
### 文档预览
![](https://gcore.jsdelivr.net/gh/sx-code/tuchuang@main/mypan/mypan-doc.png)

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## 自定义项目

See [Vite Configuration Reference](https://vitejs.dev/config/).

## 项目初始化

```sh
npm install
```

### 编译运行

```sh
npm run dev
```

### 编译构建

```sh
npm run build
```

### 代码格式化 [ESLint](https://eslint.org/)

```sh
npm run lint
```
