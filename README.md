# Zekeeparm 浏览器机械臂仿真

在线演示：https://leo66600.github.io/zekeeparm-web-mujoco/

本仓库仅包含 Vite 构建生成的静态网页、MuJoCo WASM 和仿真模型。网页仅运行浏览器仿真，不连接 ROS、串口或真实机械臂。

源项目位于用户工作区的 `web_mujoco/`。界面交互与工作台场景参考 [Yang-Ci/Rebot_Arm_AGV](https://github.com/Yang-Ci/Rebot_Arm_AGV/tree/445b48d5fd9fef8050c8a9ef5fd6ab32e3ace5cf/web_mujoco)；机械臂模型来自 Zekeeparm 工作区。上游参考仓库未提供根目录代码许可证，本部署不新增或声明其许可证。

GitHub Pages 从 `main` 分支根目录发布。更新时在本地源项目运行 `npm test` 和 `npm run build`，将 `dist/` 的内容同步到本仓库，保留 `.nojekyll` 和本说明后提交。回滚可还原到已验证的历史提交并推送。
