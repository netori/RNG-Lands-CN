# Changelog / 更新日志

## [1.0.1] - 2026-10-18（修复 BND4 布局；downloads 重打包，文件名不变）

修复 `msg/zhocn/*.msgbnd.dcx` 的 BND4 哈希表布局：之前用的是 soulstruct 的私有布局
（24 字节表头 + 相对偏移），游戏本体能读，但 **Elden Ring Randomizer** 在
`SoulsFormats.BinderHashTable.Assert` 处会断言失败：
`Read Byte: 0x0 | Expected: 0x10` —— 用「Merge other mod」合并本补丁时整次随机化会中止。
现已改为 FROM / SoulsFormats 标准布局（16 字节表头 + 绝对偏移）；
`downloads/` 下 16 个 zip 已用修正后的文件重新打包（文件名与版本号不变），
`SHA256SUMS.txt` 已同步更新。

## [1.0.0] - 2026-10-17

首个公开版本。

- 覆盖 RNG Lands 0.7.2 全部 16 个内容组（Ruby / Apache / Pack 10 的 14 个配置）：
  - 约 155 万条文本槽位全部有中文；其中约 33.9 万条为官方简中继承；
  - `item_dlc02` 每个变体写入 95,720 条译文；
  - 物品名、物品说明、随机故事、菜单、教程、系统提示、HUD 警告均已覆盖；
  - `item` / `menu` / `menu_dlc02` 采用"官方逐字继承 + 跨档案补译 + 人工补译"。
- 发布 16 个变体 zip（`downloads/`），并附校验清单（`SHA256SUMS.txt`）。
- 游戏内验证：Apache 变体实测菜单、物品、随机故事均为中文（Elden Ring 1.17.1）。

### 已知

- mod 自身的 `[ERROR]` 占位条目保持原样（英文版同样为 `[ERROR]`）；
- ToS 法律文本保持英文（官方中文文件亦为英文）；
- `script/talk` 与 `event` 文本不在本补丁范围内。
