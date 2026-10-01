# constellation-dashboard

108颗低轨星座：福建、马来西亚遥感重访及导航通信比较。

本仓库仅包含可公开的静态展示版，不含MATLAB源码、本机日志或大型MAT结果。
包含4个交互页面：项目总览、遥感重访、业务取舍、验收证据。
数据来自MATLAB R2026a仿真输出。计算流程完成不等于所有业务门限达标。

## 发布

GitHub仓库 Settings → Pages → Source 选择 Deploy from a branch，选择 main 和 /(root)，点击 Save。
无需安装依赖或运行构建命令；根目录 .nojekyll 保证静态文件直接发布。
网站发布完成后，以Pages设置页显示的 Visit site 地址为准。

## 数据与许可

页面与附带数据公开可读。边界许可和来源见 [data/SOURCES.md](data/SOURCES.md)。
马来西亚边界署名 OpenStreetMap contributors，适用 ODbL 1.0；福建源边界为 Public Domain。
不对原项目代码或其他内容额外授予开源许可证。
本项目不提供在线MATLAB重算，也不代表真实在轨星座的运营能力。
