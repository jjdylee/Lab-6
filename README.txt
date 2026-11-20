CCT360 Lab 6 — Cookie Days

打开方式：解压后用 VS Code 打开 Cookie-Lab6 文件夹，右键 index.html，选择 Open with Live Server。不能双击 HTML 测试模块脚本。

范围：沿用 Week 9 的 navbar/drawer、carousel、card、details/summary、dialog 和六字段表单；无额外自写 JavaScript。Bootstrap 文件来自本机 Week 9/resources.zip，版本 6.0.0-alpha.1。自定义 CSS 共 14 行，没有布局规则。

图片：6 张原创 SVG 柴犬插图，轮播复用前 3 张，每张小于 500KB；页面底部已注明 AI 辅助。没有使用 Wildlife 图片。你可以把插图换成自己的 Cookie 照片，同时修改路径和 alt。

理解代码：md:col-6 是中屏每行两张，lg:col-4 是大屏每行三张；h-100 让卡片填满所在行高度；data-bs-target 必须对应 id；details/summary 是浏览器原生折叠；type="module" 按老师要求载入 Bootstrap JS；CSS 变量覆盖棕色主题。

表单是静态课堂练习，无后台。提交时浏览器检查必填项与邮箱格式，再返回联系页，不发送或储存留言。无需添加后台功能。

提交前还需：
1. 用 Live Server 在 390、768、1200px 检查布局。
2. 检查菜单的打开/X/Escape、轮播前后按钮、六个弹窗和折叠、Tab/Enter、表单必填验证以及 Console。
3. 在 validator.w3.org 验证两页 HTML。
4. 推送你自己的 GitHub 仓库，按真实制作/修改过程留下至少 6 条清晰 commit。不要伪造制作历史。
5. GitHub Settings → Pages → Deploy from a branch，选择 main、/(root)，保存。
6. 打开发布后的页面再次检查，在 Quercus 提交 Repository URL 和 GitHub Pages URL。

Lab 文件第一页的 Pure CSS Only (No Frameworks) 与后面的具体要求冲突。本作品遵循正文、评分表及 Week 9 一致要求：使用老师给的 Bootstrap 6。
