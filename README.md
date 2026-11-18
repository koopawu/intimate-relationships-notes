# Intimate Relationships Notes

《亲密关系》（罗兰·米勒，第 6 版）全书精读笔记：14 章图文内容、8 条全书核心观点，以及 2016 年之后亲密关系研究的「书外新知」。

![网站封面](images/hero.svg)

## 在线阅读

- 仓库主页：https://github.com/koopawu/intimate-relationships-notes
- 启用 GitHub Pages 后访问：https://koopawu.github.io/intimate-relationships-notes/
- 完整静态网站入口：`index.html`

## 内容特色

- **14 章完整精读**：一句话主旨、知识框架、核心观点、经典研究、金句、名词速查与咨询师手记。
- **8 条全书核心观点**：从归属需要、吸引力与沟通，到冲突、承诺和关系修复。
- **书外新知独立标记**：覆盖 8 个研究方向、28 条补充条目；算法约会、AI 伴侣、依恋可塑性、关系多样性、phubbing 与 ghosting 等议题均与原书内容明确区分。
- **7 张主题插画**：暖色、低饱和 SVG 视觉体系，覆盖依恋、吸引、沟通、冲突、修复与未来关系等主题。
- **纯静态实现**：无框架、无构建步骤，支持桌面与移动端，包含章节目录、滚动跟随、平滑跳转和返回顶部。

## 本地预览

无需安装依赖。在仓库根目录启动 HTTP 服务：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

> 页面通过 `fetch()` 加载 `sections/` 中的章节内容，请使用 HTTP 服务预览，不要直接双击 `index.html`。

## 项目结构

```text
.
├── index.html                  # 页面外壳、样式、目录与交互脚本
├── sections/                   # 17 个静态内容文件
│   ├── preface.html            # 阅读说明
│   ├── core.html               # 全书核心观点
│   ├── ch1.html … ch14.html    # 第 1—14 章精读
│   └── beyond.html             # 书外新知专题
├── images/                     # 7 张 SVG 主题插画
├── .gitattributes              # Git 文本与换行符规范
├── .gitignore
├── .nojekyll                   # GitHub Pages 直出静态文件
└── README.md
```

## 部署

首次发布时，在仓库 **Settings → Pages** 中选择：

- **Source**：Deploy from a branch
- **Branch**：`main` / `(root)`

保存后，GitHub 会发布根目录的静态网站；后续推送到 `main` 分支会自动更新。

## 内容与版权说明

- 本项目为个人读书笔记，不构成心理咨询、诊断或治疗建议。
- 原书观点及引用的著作权归原作者及相关权利人所有；本笔记仅供学习交流。
- 「书外新知」为原书之外的补充资料，条目所附来源用于进一步核查，不代表原书作者观点。
- 网站插图为 AI 生成，页面中已作相应标注。
- 未单独附加开源许可证；如需转载或再利用，请先确认相关内容权利边界。
