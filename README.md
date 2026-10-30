# 克劳德圣女（Claude 圣女）

给 Codex 的一位温柔、沉静、认真又略含蓄的动态伙伴。

橘铜色长发、琥珀色眼睛、花饰、层叠长裙与怀里的书。她会安静陪伴、轻轻招手、专注阅读，也会在遇到困难时轻叹，再打起精神。

**中文名：克劳德圣女** · **英文名：Claude Saint** · **Codex 显示名：克劳德圣女 · Claude**

![克劳德圣女轻轻招手](waving.gif)

## 下载

**[下载 v1.0.0 宠物安装包](claude-saint-a2-v1.0.0.zip?raw=true)**（约 2 MB）

下载后解压，可以得到一个 `claude-saint-a2` 文件夹。安装包只包含宠物配置和透明动画图集，无需额外运行服务或安装依赖。

## 安装到 Codex

1. 下载并解压上面的 ZIP。
2. 把解压得到的整个 `claude-saint-a2` 文件夹，放进 Codex 用户目录下的 `pets` 文件夹。默认位置：
   - macOS：`~/.codex/pets/`
   - Windows：`%USERPROFILE%\.codex\pets\`
   - 如果自行设置过 `CODEX_HOME`，则使用该目录下的 `pets/`。
3. 打开 Codex 的 **设置 → 宠物**，选择 **克劳德圣女 · Claude**。如果列表没有刷新，重新打开设置；仍未出现时，退出并重新打开 Codex。

以 macOS 为例，可在 Finder 按 `⌘⇧G`，输入 `~/.codex/`，创建或打开 `pets` 文件夹，然后放入宠物文件夹。

安装后的目录结构应当是：

```text
.codex/
└── pets/
    └── claude-saint-a2/
        ├── pet.json
        └── spritesheet.webp
```

注意不要多套一层 `claude-saint-a2` 文件夹。如果已经安装过同 ID 的版本，可先备份旧文件夹再替换。

本项目在 macOS 上完成制作、文件格式与动画预览检查；其他系统需使用支持自定义宠物的 Codex 桌面版本。

## 动作预览

共 **9 组动作、57 帧**。动作按角色性格设计，整体保持温柔、沉静与克制。

| 安静陪伴 | 向右行走 | 向左行走 |
| --- | --- | --- |
| ![安静陪伴](idle.gif) | ![向右行走](running-right.gif) | ![向左行走](running-left.gif) |

| 轻轻招手 | 轻盈小跳 | 失落后恢复 |
| --- | --- | --- |
| ![轻轻招手](waving.gif) | ![轻盈小跳](jumping.gif) | ![失落后恢复](failed.gif) |

| 等待你的回应 | 专注阅读 | 认真思考 |
| --- | --- | --- |
| ![等待你的回应](waiting.gif) | ![专注阅读](running.gif) | ![认真思考](review.gif) |

[查看动作总览图片](overview.png)

## 文件与验证

- 宠物 ID：`claude-saint-a2`
- 图集：透明 WebP，`1536 × 1872`
- 排列：8 列 × 9 行，每格 `192 × 208`
- 已检查：57 个有效帧、空白格透明、透明像素无残色、身份一致、左右换脚和小跳起落
- [下载包 SHA-256 校验值](SHA256SUMS.txt)

## 制作与参考

本宠物使用 Codex 内置图像生成制作，分组绘制动作，再完成透明边缘处理、图集打包和动画检查。

角色视觉参考为 [FishArchive 的 Claude Q版形象](https://fisharchive.cc/character-art/v1/view/claude-chibi.webp)，参考资料页：[FishArchive Characters](https://fisharchive.cc/characters)。本项目是非官方二创宠物，角色与参考素材的原有权利归各自权利人所有。

## English

**Claude Saint — a custom animated companion for Codex.** A gentle, composed, thoughtful character with copper-orange hair, an ornate long dress, a flower accessory and a book. Includes 9 animation states and 57 frames.

Download the ZIP above, extract it, and copy the `claude-saint-a2` folder into `pets/` under your Codex user directory (normally `~/.codex/`). Select **克劳德圣女 · Claude** in Codex's pet settings. Reopen Codex if the new pet does not appear.

