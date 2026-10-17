# RNG Lands 简体中文补丁（v1-20261017）

> 全量回读验收 64/64 PASS；游戏内验证 PASS（菜单/物品/随机故事为中文）。
> 生成：2026-10-17T23:45:34

## 一、选哪个包

RNG Lands 有多个发行包（Ruby / Apache / Pack 10）与多个配置。**找准你玩的那一个**：

| 变体 | 补丁包 | 适用 mod 目录 |
|---|---|---|
| apache / base | `RNG-Lands-CN-apache-base-recommended_increased-v1-20261017.zip` | `RNG Lands - Apache 3229 0.7.2 2026-10-05T19-52Z AHk37cNKM\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / distant_randomized_1 | `RNG-Lands-CN-pack_10-distant_randomized_1-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 distant randomized 1\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / distant_randomized_2 | `RNG-Lands-CN-pack_10-distant_randomized_2-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 distant randomized 2\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / golden_randomized_distant_1 | `RNG-Lands-CN-pack_10-golden_randomized_distant_1-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 golden randomized distant 1\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / golden_randomized_distant_2 | `RNG-Lands-CN-pack_10-golden_randomized_distant_2-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 golden randomized distant 2\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / golden_targeted_1 | `RNG-Lands-CN-pack_10-golden_targeted_1-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 golden targeted 1\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / golden_targeted_2 | `RNG-Lands-CN-pack_10-golden_targeted_2-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 golden targeted 2\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / randomized_balanced_1 | `RNG-Lands-CN-pack_10-randomized_balanced_1-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 randomized balanced 1\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / randomized_balanced_2 | `RNG-Lands-CN-pack_10-randomized_balanced_2-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 randomized balanced 2\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / randomized_golden_1 | `RNG-Lands-CN-pack_10-randomized_golden_1-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 randomized golden 1\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / randomized_golden_2 | `RNG-Lands-CN-pack_10-randomized_golden_2-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 randomized golden 2\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / targeted_balanced_1 | `RNG-Lands-CN-pack_10-targeted_balanced_1-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 targeted balanced 1\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / targeted_balanced_2 | `RNG-Lands-CN-pack_10-targeted_balanced_2-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 targeted balanced 2\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / targeted_golden_distant_1 | `RNG-Lands-CN-pack_10-targeted_golden_distant_1-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 targeted golden distant 1\recommended increased difficulty`（recommended / vanilla 通用） |
| pack_10 / targeted_golden_distant_2 | `RNG-Lands-CN-pack_10-targeted_golden_distant_2-recommended_increased-v1-20261017.zip` | `RNG Lands - Pack 10 3229 0.7.2 2026-10-05T19-49Z OS1DuRs7x\RNG Lands 0.7.2 targeted golden distant 2\recommended increased difficulty`（recommended / vanilla 通用） |
| ruby / base | `RNG-Lands-CN-ruby-base-recommended_increased-v1-20261017.zip` | `RNG Lands - Ruby 3229 0.7.2 2026-10-04T13-35Z kRGZWDlGa\recommended increased difficulty`（recommended / vanilla 通用） |

* 每个包对 `recommended increased difficulty` 与 `vanilla difficulty` **两个难度都通用**
  （同源文件，内容一致）；
* 不想逐个挑：直接用 `RNG-Lands-CN-all-variants-v1-20261017.zip`（按变体子目录组织）。

## 二、安装

1. 打开你的 RNG Lands mod 目录，例如
   `...\RNG Lands - Apache 3229 0.7.2 ...\recommended increased difficulty\`
2. 把补丁包里的 `msg` 文件夹**合并**进去（补丁只新增 `msg/zhocn/`，不改 mod 原文件）
3. 启动游戏；**游戏语言必须是「简体中文」**

## 三、卸载

删除 mod 目录下的 `msg/zhocn/` 文件夹即可。

## 四、范围与已知

* 覆盖 `msg` 文本：物品名/说明、随机故事、菜单与系统提示；
* 游戏语言不是简体中文时读的是 `engus`，补丁不生效；
* `[ERROR]` 占位条目（mod 原文即 `[ERROR]`）保持原样；ToS 法律文本官方中文档也是英文；
* `script/talk` 与 `event` 文本不在这套 BND 里，未处理。

## 五、校验

`MANIFEST.json` 里有每个 zip 与每个 `.dcx` 的 sha256 和大小。
