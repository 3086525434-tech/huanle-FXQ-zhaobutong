欢乐找不同_手机稳定V3

已修复/优化：
1. 删除 package.json 和 vercel.json，避免 Vercel 误判为需要构建的项目。
2. 每关统一为 60 秒，首页和弹窗文案同步。
3. 修复游戏初始倒计时仍显示 30 秒的问题。
4. 增加手机 touchstart 点击支持，微信/手机浏览器点击更稳定。
5. 保持 assets 相对路径，适合 Vercel / GitHub / Netlify 静态部署。

上传方法：
1. 解压本 zip。
2. 进入文件夹内部。
3. 把 index.html 和 assets 文件夹上传到 GitHub 仓库根目录。
4. 不要上传 package.json / vercel.json。
5. Commit changes 后，Vercel 会自动重新部署。

手机打不开排查：
- 一定使用 Vercel 链接：https://xxx.vercel.app
- 不要用 github.io 链接。
- 微信里打不开时，点右上角选择“在浏览器打开”。
