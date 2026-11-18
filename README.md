# Ponytail CN

**用最少的新代码，把整个问题解决。**

## 功能与流程

先读调用方与现有结构，再复用已有代码、标准库和已安装依赖。保留最小完整改动、lite/full/ultra 三档、必要校验与错误处理，以及对未检查内容的简短说明。

## 小幅增加

- 中文启停、档位和状态查询口令。
- 区分“解释简单点”与“代码实现更简单”，不误删需求。
- 中文交付只讲实际改动、未验证部分与必要风险。
- 明确减法只作用于授权范围，保留用户既有代码和未提交工作。

## 安装与调用

```bash
npx skills add batespaige357-tech/ponytail-cn --skill ponytail-cn
```

对助手说“开启 ponytail-cn，完整档”；Codex 可用 `$ponytail-cn`。也可把 `skills/ponytail-cn` 整个文件夹复制到助手的技能目录。

档位：轻量档 lite、完整档 full（默认）、严格档 ultra。用“退出 ponytail-cn”恢复正常模式。“当前档位”只查询会话状态，不写全局配置。

本项目只提供基础编码风格 Skill，不打包上游 hooks、插件运行时、审计或 review 等其他技能。基础核心正文完整保留，不依赖安装完整 Ponytail 插件。没有脚本、示例网页或效果截图。

## 来源与许可

基于 [dietrichgebert/ponytail](https://github.com/dietrichgebert/ponytail)，由本仓库维护。

MIT，保留 DietrichGebert 版权和完整许可证。版本与改动见 [CHANGES.md](CHANGES.md)。

已检查原正文完整保留、UTF-8、本地引用与技能格式。没有真实模型编码或模式切换盲测，不保证减少多少代码或 token；未运行前端编译。
