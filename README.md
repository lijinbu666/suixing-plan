# 随行计划

安卓个人计划助手的公开界面更新文件。GitHub Pages仅存放HTML/CSS/JavaScript，不存放任务、聊天、API Key或APK签名文件。

## 首次发布
仓库 Settings → Pages → Build and deployment：Source选择 Deploy from a branch，Branch选择 main，目录选择 / (root)，保存。

发布后固定更新地址：
https://lijinbu666.github.io/suixing-plan/index.html

## 手机配置
覆盖安装随行计划0.8或后续兼容版本。设置 → 打开手机设置 → 配置界面更新地址，填写上述URL。返回网页设置，点击检查并更新界面。启动或回到前台时自动检查（最短60秒间隔），没有输入或待确认变化时切换新版；否则延后切换。下载失败保留旧页面。断网可查看已保存计划并接收本地提醒。应用完全关闭时不会主动推送更新通知。

## 后续更新
修改main分支的index.html，Pages发布完成后移动端可获取。内置安卓桥协议变化仍需APK升级；兼容协议内页面样式、排版和图表可在线更新。HTML必须保留suixing-interface-v1标记，所有依赖内嵌。请勿写入任何密钥或个人记录。

GitHub Pages托管可免费使用公开仓库，百炼AI费用独立。国内网络连通性以手机实测为准。本仓库文件直接在浏览器打开仅显示连接说明，实际任务界面须在安卓应用内使用。
