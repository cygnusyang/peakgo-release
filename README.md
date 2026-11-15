# peakgo-release

PeakGo（峰行）Android 版对外的静态页面仓库。

目前只有隐私政策：

- <https://cygnusyang.github.io/peakgo-release/> — Google Play 商店「隐私政策」字段填这一条
- <https://cygnusyang.github.io/peakgo-release/privacy/> — 同一页的固定路径别名

页面为单文件、零外部依赖（无 CDN、无字体、无统计），跟随系统深浅色。改文案只需改 `index.html` 与 `privacy/index.html`（两处同内容），提交后 GitHub Pages 自动重建。

隐私政策正文的事实依据：Android 清单未声明 `INTERNET` 权限，定位与相机数据仅在本机参与计算，不上传。
