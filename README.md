# 广智新 · 企业工作空间

PC V14 与 APP 的公开交互设计原型，采用红色主色与橘色点缀。

## 在线体验

- 统一入口：https://rh3in.github.io/GX-home/
- PC 工作台：https://rh3in.github.io/GX-home/pc/
- 信息门户：https://rh3in.github.io/GX-home/pc/#portal
- AI Agent：https://rh3in.github.io/GX-home/pc/agent.html
- APP：https://rh3in.github.io/GX-home/app/

## V14 AI 工作空间

新增智能体与技能、知识库、云盘、数字员工管理演示入口；历史任务支持搜索与收藏。核心能力精简为制作 PPT、分析数据、创作文档和咨询问答，采用红色主调、白色输入框和原始 3D IP。模型名称展示为 qwen3.8-27b。联网、语音和模型服务为交互入口演示。

## 内容

PC 版包含常用功能、AI 主动服务与提醒、统一待办、竖向日程、审批、会议、信息门户与 AI 助手挂件。APP 包含工作台、信息门户、AI 助理、消息中心和我的五个入口。手机访问 APP 自动适应视口，电脑访问显示手机画框。

两份 HTML 均内嵌所需图片和脚本，无需构建或安装依赖，点击上方入口即可体验。设计包保存在 downloads/，包含 SVG、PNG、可编辑 JSON 和交付说明。

## 仓库结构

- index.html：双端体验入口
- pc/index.html：PC V14 交互原型
- pc/agent.html：V14 AI 工作空间直达入口
- app/index.html：APP 交互原型
- assets/：入口预览图片
- downloads/：PC 与 APP 完整设计包
- .nojekyll：直接发布静态文件

## 部署与更新

使用 GitHub Pages，从 main 分支的根目录发布。后续更新相应 HTML 并推送到 main 即可重新发布。所有站内链接使用相对路径，支持 /GX-home/ 项目路径。

本地可直接打开 HTML，也可在仓库根目录运行任意静态文件服务器。

## 演示范围

这是设计与前端交互原型。数据、新闻、日程、消息和 AI 回复用于界面演示，尚未接入真实登录、企业业务系统、消息推送与大模型服务。
