# N 网（NexusMods）上传文件说明

> 版本：**1.0**（2026-10-17）｜适用于 RNG Lands 0.7.2 / Elden Ring 1.17.x
> 每个文件都已在本地做过：sha256 校验 + `testzip` 完整性 + 抽包回读验证。

## 上传哪个文件

| 上传文件 | Nexus 分类 | 文件名 / 版本 | 给谁用 |
|---|---|---|---|
| `RNG_Lands_CN_Patch_Ruby_1.0.zip` | Main files | Chinese Patch - Ruby, 1.0 | RNG Lands **Ruby** 版玩家 |
| `RNG_Lands_CN_Patch_Apache_1.0.zip` | Main files | Chinese Patch - Apache, 1.0 | RNG Lands **Apache** 版玩家 |
| `RNG_Lands_CN_Patch_Pack10_1.0.zip` | Main files | Chinese Patch - Pack 10, 1.0 | RNG Lands **Pack 10** 版玩家（14 个配置全含） |
| `MANIFEST.json` | Optional / Misc | Checksums, 1.0 | 可选：校验清单（也可不传） |

## 文件规格

| 文件 | 大小 | SHA-256 |
|---|---:|---|
| `RNG_Lands_CN_Patch_Ruby_1.0.zip` | 4.76 MB | `573fb12b8ca682a5d10490905908000e117f5f537c6690f9e25c4c2d666b4ff6` |
| `RNG_Lands_CN_Patch_Apache_1.0.zip` | 4.76 MB | `00c32588a3dd0ced0ecdee39a4563f5ba183ff6241149d124ceb9f2e31b8bee1` |
| `RNG_Lands_CN_Patch_Pack10_1.0.zip` | 67.08 MB | `5cbae2acbced3dd000a17852362de5962b2068e79c97f46892d9f46753e40b9c` |

## 每个 zip 里是什么

* `recommended increased difficulty/msg/zhocn/*.dcx` 与 `vanilla difficulty/msg/zhocn/*.dcx`
  （Pack 10 则是 `<配置名>/<难度>/msg/zhocn/*.dcx`，14 个配置 × 2 难度）；
* 4 个文件：`item.msgbnd.dcx`、`item_dlc02.msgbnd.dcx`、`menu.msgbnd.dcx`、`menu_dlc02.msgbnd.dcx`；
* `安装说明.txt`（中文）与 `README.txt`（English）；
* **不含**原 mod 的任何文件。

## 建议的 Nexus 文件描述（可直接贴）

* Ruby：`Simplified Chinese patch for RNG Lands - Ruby. Merge into your Ruby mod root (both difficulties included). Requires RNG Lands 0.7.2 and game language set to Simplified Chinese.`
* Apache：`Simplified Chinese patch for RNG Lands - Apache. Merge into your Apache mod root (both difficulties included). Requires RNG Lands 0.7.2 and game language set to Simplified Chinese.`
* Pack 10：`Simplified Chinese patch for RNG Lands - Pack 10 — all 14 configs × 2 difficulties included. Merge into the Pack 10 root. Requires RNG Lands 0.7.2 and game language set to Simplified Chinese.`

## 版本策略

* 当前版本号：**1.0**（首个公开版）；
* 以后更新只给对应 variant 换 zip，版本号递增（1.1、1.2…），并在 Changelog 写明改了什么。
