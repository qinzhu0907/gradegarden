# Gradegarden

> A calmer way to keep score. Plan a final exam, calculate a course grade, and estimate your GPA.

Gradegarden is a small, dependency-free, bilingual grade-planning website. It runs entirely in your browser; grades and course data are not sent to a server.

**GitHub Pages:** `https://qinzhu0907.github.io/gradegarden/` (available after the first successful deployment) · **[简体中文](#简体中文)**

## Features

- Final exam target calculator with weighted-average and total-points modes
- Course grade calculator with standard and plus/minus letter-grade scales
- Category-weighted course grade calculator with configurable dropped-lowest scores
- Editable course list with credits, letter grades, and regular, Honors, or AP/IB course types
- Cumulative GPA goal planner based on completed and upcoming credits
- GPA estimates using 4.0, 4.3, 5.0, and illustrative UC-style scales
- Custom school grade cutoffs, grade points, honors bonus, and GPA cap
- English and Simplified Chinese interface
- Responsive layout for desktop and mobile
- No build step, dependencies, account, or data collection
- Course data and custom rules are saved locally in the browser

GPA policies differ between schools. The presets are planning estimates and are not official transcript calculations. The UC-style preset is an approximation.

## Run locally

Open `index.html` in a modern browser. There is no install or build step.

## Deploy with GitHub Pages

The included workflow publishes the site from the repository root when changes are pushed to `main`. In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions** if it is not already selected.

## Contributing

Bug reports, accessibility fixes, translations, and focused improvements are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) before opening an issue or pull request.

## License

Released under the [MIT License](LICENSE).

---

## 简体中文

Gradegarden 是一个无需依赖、支持中英文的成绩规划网站，可用于估算期末目标分、课程总评和 GPA。所有成绩仅在浏览器中计算，不会发送到服务器。

### 功能

- 加权平均与总分制期末目标分计算
- 标准制和加减等级制课程总评
- 按作业类别加权计算，并支持丢弃最低分
- 可编辑课程、学分、字母成绩和课程类型
- 根据已修与计划学分反推累计 GPA 目标
- 4.0、4.3、5.0 及示意性的 UC 风格 GPA 估算
- 自定义等级分界、绩点、荣誉课程加分和 GPA 上限
- 英文与简体中文界面，适配桌面和手机
- 无需安装依赖、注册账号或构建
- 课程数据和自定义规则仅保存在本机浏览器

不同学校的 GPA 规则并不相同。这里的预设仅供规划参考，不是官方成绩单换算；UC 风格仅为近似示意。

### 本地运行

使用现代浏览器打开 `index.html` 即可，无需安装或构建。

### 参与贡献

欢迎提交问题、无障碍改进、翻译和小范围功能改进。提交前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。

### 许可证

本项目采用 [MIT 许可证](LICENSE)。
