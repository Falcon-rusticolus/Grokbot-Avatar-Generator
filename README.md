# grokbot-avatar

把一张人物照片转换成 grokbot 风格方形头像。

## 安装

（对于Codex）双击 `install-grokbot-avatar.cmd`。脚本会把 `grokbot-avatar` 文件夹复制到：

```text
%USERPROFILE%\.codex\skills\grokbot-avatar
```

手动安装则直接将 `grokbot-avatar` 文件夹复制到skills文件夹中

## 检验

安装后在下一次对话中说：

> 帮我生成grokbot风格头像图片

然后附上一张包含人物的清晰照片。

## 使用

- 一次只处理一个人物。
- 照片只用于提供身份特征；背景、光线、原姿势和复杂服装不会照搬。
- 默认生成深炭灰背景、1:1 超近景头像。
- 生成结果会自动保存到当前任务的 `outputs/` 目录，并直接在对话中展示。

## 目录

```text
grokbot-avatar/
|-- SKILL.md
|-- agents/
|   \-- openai.yaml
|-- assets/
|   |-- reference01.png
|   |-- reference02.png
|   \-- reference03.png
\-- references/
    \-- prompt-template.md
```
