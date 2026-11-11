# 工作台

前端：[https://liangzai4322.github.io/workbench/](https://liangzai4322.github.io/workbench/)

域名入口：[https://liangzai666.com/workbench](https://liangzai666.com/workbench)

单用户项目工作台。输入访问密钥后读取服务器数据，修改自动同步。密钥、项目数据和数据库不包含在此公开仓库中。

成功登录后会在当前浏览器记住密钥，新标签页及重启浏览器后无需重复输入。点击“锁定”会清除记住的密钥；清除网站数据或使用无痕窗口后需要重新输入。

GitHub Pages 仅托管这个单文件界面，无构建依赖；后端在日本服务器，API 使用 HTTPS。

本地旧版若有修改，请先导出 JSON，再在网页中导入。导入会替换云端的全部项目。

多设备打开时，进入页面或刷新会获取最新数据。同时编辑导致版本冲突时会保留本机修改，并提示导出后重新加载。
