# POS Demo Template

可复用的 POS 需求演示模板。每一个需求 demo 建议从本仓库创建，并独立部署为 GitHub Pages。

## 新 demo 命名

`pos-demo-<module>-<number>`，例如：`pos-demo-payment-002`。

## 发布

推送到 `main` 后，GitHub Actions 会将本仓库发布为 GitHub Pages。首次使用时，请在 GitHub 仓库的 **Settings → Pages** 中选择 **GitHub Actions** 作为发布来源。

## 必填信息

发布前更新下面的项目资料：

| 字段 | 示例 |
| --- | --- |
| 需求名称 | 付款码支付优化 |
| 模块 | Payment |
| 需求编号 | POS-502 |
| 负责人 | 张三 |
| Figma | URL |
| 评审状态 | 待评审 |
| Demo 链接 | 发布后填写 |

## 目录

```text
demo/                 静态演示页面
.github/workflows/    自动发布工作流
README.md              需求与交接说明
```
