RepReady PWA 部署包（Windows 电脑可操作）

文件说明：
- index.html：当前 RepReady 网页原型
- manifest.webmanifest：安装名称、图标和独立窗口配置
- service-worker.js：基础缓存，支持部分离线打开
- icons/：手机桌面图标

重要：
1. 不能把这个 ZIP 直接当作 iPhone App 安装。
2. 需要先把 ZIP 解压，并将里面所有文件上传到支持 HTTPS 的静态网站托管服务。
3. 部署后用 iPhone 的 Safari 打开网站地址，再点“分享”→“添加到主屏幕”，并开启“作为 Web App 打开”（如果出现该选项）。
4. 这是可安装网页应用，不是 App Store 原生 App；当前心率仍为模拟数据，不会读取 Apple Watch。
