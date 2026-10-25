# 任务规划 · 额度体验原型

刘立潮的产品方向交互原型，用于演示成功、额度耗尽、生成失败和同账号请求拦截。

基于 [题目仓库](https://github.com/bybzhwbzhh88/task-planner-interview) 的产品场景，提交材料维护于 [个人 fork](https://github.com/LiuLCDT/task-planner-interview)。

## 运行

纯静态 HTML/CSS/JavaScript，无构建步骤、无外部模型及后端连接。运行 `python3 -m http.server 4173` 后打开 `http://localhost:4173`。

GitHub Pages 发布设置：Deploy from a branch → main → / (root)。

## 演示范围

- 左侧为评审控制，右侧为产品原型。
- 普通场景自动运行；并发场景需点击生成，模拟另一页面占用时的拦截，不消耗本页额度。
- 切换场景或重置解除模拟占用，刷新重置数据。
- 登录退出、主题切换、待办完成与逐项时长为静态占位；日程结果勾选可交互。
- 模拟记录不能证明真实后端并发安全。

原题目相关版权声明保留于 LICENSE 与 THIRD_PARTY_NOTICES.md。
