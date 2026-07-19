<div align="center">
  <h1>步天工程社 · GitHub 默认配置</h1>
  <p><a href="README.md">English</a> | 简体中文</p>
  <p>
    <img src="https://img.shields.io/github/last-commit/butian-club/.github?style=flat-square" alt="最后提交" />
    <img src="https://img.shields.io/github/license/butian-club/.github?style=flat-square" alt="许可证" />
  </p>
</div>

## 项目简介

步天工程社的 GitHub 组织简介与社区健康文件单一真源。组织内仓库从这里继承 issue
模板、PR 清单、贡献指南与安全策略，不在每个仓库重复维护。

## 项目特性

🏠 **组织简介** —— `profile/README.md` 会显示在组织主页，并提供完整简体中文镜像。

📮 **协作默认值** —— 双语 issue 模板、PR 清单与贡献指南统一协作方式。

🔒 **安全策略** —— 安全漏洞通过 GitHub 私密报告渠道提交，不在公开 issue 中披露。

## 快速开始

GitHub 会自动将这些文件应用到没有同类本地文件的组织仓库。仓库可通过添加本地文件覆盖
默认值。若某仓库的 `.github/ISSUE_TEMPLATE/` 中存在任意文件，则会整体覆盖继承的
issue 模板目录。

## 项目结构

```bash
.github/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md           # 共享 bug 报告
│   │   ├── config.yml              # issue 创建设置
│   │   └── feature_request.md      # 共享功能建议
│   ├── CONTRIBUTING.md             # 贡献工作流
│   ├── PULL_REQUEST_TEMPLATE.md    # PR 清单
│   └── SECURITY.md                 # 私密漏洞报告策略
├── profile/
│   ├── README.md                   # 英文组织简介
│   └── README.zh-Hans.md           # 简体中文组织简介
├── .gitignore                      # 忽略的本地文件
├── LICENSE                         # 代码许可协议
├── README.md                       # 英文文档
└── README.zh-Hans.md               # 简体中文文档
```

## 许可协议

本项目代码采用 [MIT 许可协议](LICENSE)。
