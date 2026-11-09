# 人工智能与设计创新课程网站

访问地址：https://jhbutter.github.io/AI-and-Design-Innovation/

纯静态课程网站，包含课程首页和四周、十二次课的教学安排。右上角的「中文 / EN」支持即时切换，两页共用语言偏好。英文直达链接：https://jhbutter.github.io/AI-and-Design-Innovation/?lang=en

## 本地预览

运行 `python3 -m http.server 8000 --directory dist`，访问 http://localhost:8000 。无需安装依赖或编译。

## 文件

- `dist/index.html`：中文首页与教师信息。
- `dist/schedule/index.html`：中文教学安排。
- `dist/i18n.js`：英文翻译、语言切换、偏好保存与跨页语言参数。
- `dist/styles.css`、`dist/script.js`：样式与导航交互。
- `dist/assets/`：课程标志与教师照片。

修改中文文案时同步更新 `dist/i18n.js` 对应翻译。核对中英文首页、教学安排、移动端布局和站内链接。推送 `main` 后，GitHub Actions 将 `dist/` 发布到 GitHub Pages。
