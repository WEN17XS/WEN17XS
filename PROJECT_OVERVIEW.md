# Project Overview

## 项目目标

这是 GitHub 用户 `WEN17XS` 的同名主页仓库，用于维护个人主页 `README.md` 展示内容。

## 技术栈

- Markdown：维护 GitHub 个人主页内容。
- GitHub Actions：定时生成动态贡献图资源。

## 目录结构

- `README.md`：GitHub 个人主页展示内容。
- `.github/workflows/`：自动化工作流配置。
- `PROJECT_OVERVIEW.md`：项目长期说明文档。

## 核心流程

- GitHub 会将同名仓库 `WEN17XS/WEN17XS` 的 `README.md` 展示在个人主页。
- `snake.yml` 工作流每天生成 GitHub 贡献图贪吃蛇 SVG，并推送到 `output` 分支。
- `README.md` 通过 raw.githubusercontent.com 地址引用 `output` 分支中的 SVG。

## 运行与测试

- 本项目没有本地构建或测试命令。
- 贡献图贪吃蛇可在 GitHub Actions 页面手动触发 `Generate contribution snake` 工作流验证。

## 关键约定

- 进行代码或配置变更前先阅读本文件。
- 任务结束后仅补充长期有效的项目事实、命令、接口、约定或风险。

## 已知风险

- GitHub Actions 需要仓库启用 Actions，并允许工作流写入内容权限。
- 如果默认分支名称或 GitHub 用户名变化，需要同步更新 README 引用和工作流配置。
