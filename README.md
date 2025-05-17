# 花卉浇水记录系统

这是一个简单的花卉浇水记录系统，允许用户记录花卉浇水情况，并将数据存储在GitHub上。

## 功能

- 记录花卉浇水信息
- 按花卉类型筛选记录
- 自动同步数据
- 响应式设计，适配移动设备

## 如何使用

1. 访问网站：https://ws-ergua.github.io/flower-watering/
2. 填写浇水日期、花卉种类和记录人
3. 点击"添加记录"按钮提交记录
4. 记录将作为GitHub Issue提交，管理员审核后会自动显示在网站上

## 技术说明

- 前端：纯HTML、CSS和JavaScript
- 后端：GitHub Issues + GitHub Actions
- 部署：GitHub Pages

## 管理员指南

作为管理员，您可以：

1. 在GitHub仓库的Issues页面查看所有提交的记录
2. 关闭不需要显示的记录（关闭的Issue不会显示在网站上）
3. 编辑Issue内容修改记录信息
4. 手动触发GitHub Actions工作流更新数据

## 许可证

MIT
