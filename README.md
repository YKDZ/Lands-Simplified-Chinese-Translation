# Lands Simplified Chinese Translation

先前曾咨询过插件作者，发现他们采用的翻译维护平台真的很难用，故自行开设储存库维护简体中文翻译。

当前对应的插件版本：[9.2.0](https://www.spigotmc.org/resources/1lands-%E2%AD%95-land-claim-plugin-%E2%9C%85-grief-prevention-protection-gui-management-nations-wars-1-20-support.53313/updates)

## 安装使用

如果你从未修改过插件的配置文件，你大可以将所有文件直接放入 `plugins/Lands` 中并重启服务器以自动同步可能的更新。

如果你曾经修改过插件的配置文件，建议你只将 `Locale/*` 放入对应文件夹中，并将另外的配置文件作为对照，修改你目前的配置文件，以防丢失任何数据。

别忘记将 `config.yml` 中的 `general.language` 键修改为 `zh-CN`。

## 翻译内容

| 源文件 | 翻译后 |
| --- | --- |
| Locale/en-US.yml | Locale/zh-CN.yml |
| Locale/Nations/en-US.yml | Locale/Nations/zh-CN.yml |
| Locale/Wars/en-US.yml | Locale/Wars/zh-CN.yml |
| Locale/en-US_dialogs.yml | Locale/zh-CN_dialogs.yml |
| Locale/Nations/en-US_dialogs.yml | Locale/Nations/zh-CN_dialogs.yml |
| Locale/en-US_gui.yml | Locale/zh-CN_gui.yml |
| Locale/Nations/en-US_gui.yml | Locale/Nations/zh-CN_gui.yml |
| Locale/Wars/en-US_gui.yml | Locale/Wars/zh-CN_gui.yml |
| categories.yml | categories.yml |

仅翻译了可以显示在游戏内的文本，没有翻译配置文件注释等不重要的文本（因为量大且难以维护）。

与管理员相关的菜单文本的翻译可能比针对玩家的文本和菜单的要粗糙，因为插件本身提供的英文原文就很模糊。

另外，大部分管理员相关命令的提示文本（如 `/lands admin reload`）都是硬编码在插件中的，无法被翻译。

## 翻译风格

本翻译融合了部分个人风格，在此处声明，以便识别和修改：

- 所有的标点符号皆为**英文半角标点**（因为在 Minecraft 游戏内使用官方中文字体时，中文全角标点给人的观感较差，欠缺美观）
- 不使用**您**字

## 术语表

本插件使用了数个赋予了特殊含义的名词和动词（术语），它们的翻译可能随着服务器的玩法和性质等而改变，故提供术语表，方便使用 `VSCode` 等编辑器的**批量修改功能**快速地进行匹配和替换以满足各类服务器的需求。

| 术语 | 翻译 | 备注 |
| --- | --- | --- |
| nation, nations | 联邦, 国家 | 由城镇组成的实体。 |
| capital, capitals | 首都 | 建立联邦的城镇。 |
| land, lands | 城镇 | Lands 插件中的城镇领地实体；产品名 Lands 不适用此术语。 |
| area, areas | 子区域 | 城镇领土内划出的小区域。 |
| spawn, spawn point, spawnpoint, land spawn, area spawn, nation spawn, world spawn, world's spawn | 传送点 | 为城镇、子区域或联邦设置，供玩家传送前往的固定位置；世界默认出生位置不适用此译法。 |
| camp, camps | 露营地 | 临时、固定大小的城镇。 |
| wilderness | 荒野 | 没有被占领的区块。 |
| role, roles | 职位 | 城镇或联邦成员的权限控制。 |
| owner, owners | 主人 | README 将该词列为 Lands 玩法中的领域术语。 |
| tenant, tenants | 住户 | 租用或购买子区域的玩家, 统一称为住户; 包括租客和子区域买主。 |
| trust, trusts, trusted, trusting | 邀请, 加入 | 对应其他领地插件的 invite；从玩家视角也可表达为被加入。 |
| trusted player, trusted players | 成员 | 已受信任并获得成员身份的玩家。 |
| untrust, untrusted, untrusting | 移出 | 对应其他领地插件的 kick。 |
| claim, claims, claimed, claiming | 占领 | 动词义；与名词义领土区分。 |
| claim, claims | 领土 | 名词义；与动词义占领区分。 |
| unclaim, unclaims, unclaimed, unclaiming | 取消占领, 未占领, 解除占领, 取消 | README 将该词列为 Lands 玩法中的领域术语。 |
| natural flag, natural flags, natural setting, natural settings | 环境设置 | 影响区域环境行为，例如刷怪或 TNT 对方块的影响。 |
| role flag, role flags, role setting, role settings | 职位设置 | 控制职位玩家的权限，例如能否破坏方块。 |
| mainblock, mainblocks, main block, main blocks | 城镇核心 | 城镇创建时自动产生的方块结构。 |
| bank, banks | 金库 | 城镇和联邦的“银行”。 |
| storage | 仓库 | 城镇核心中的虚拟物品空间。 |
| upkeep | 维护费 | 城镇和联邦定期向服务器支付的款项。 |
| tax, taxes | 税费 | 成员定期向所属城镇或联邦支付的款项。 |
| relation, relations | 外交关系 | 城镇、联邦等在战争中的关系。 |
| ally, allies | 盟友 | README 将该词列为 Lands 玩法中的领域术语。 |
| enemy, enemies | 政敌 | README 将该词列为 Lands 玩法中的领域术语。 |
| neutral, neutrals | 中立 | README 将该词列为 Lands 玩法中的领域术语。 |
| war, wars | 战争 | README 将该词列为 Lands 玩法中的领域术语。 |
| capture block, capture blocks, capture flag, capture flags | 战旗 | 战争中攻方用于占领守方领土的信标道具；此完整短语不等同于普通动词 capture。 |
| attacker, attackers | 攻方 | README 将该词列为 Lands 玩法中的领域术语。 |
| defender, defenders | 守方 | README 将该词列为 Lands 玩法中的领域术语。 |
| tribute, tributes | 赔偿金 | 一方投降后向另一方支付的款项。 |
| war shield, war shields | 战争护盾 | 保护城镇或联邦免于战争的一段时间。 |
| expiration shield | 过期保护 | 管理员启用后，可防止非活跃城镇因过期而被删除。 |
| declaration, declarations, war declaration, war declarations | 宣战书 | 名词义，常见完整短语为 war declaration。 |
| declare, declares, declared, declaring, declare war, declares war, declared war, declaring war | 宣战 | 动词义，常见完整短语为 declare war。 |
| remove tenant, remove the tenant, remove the current tenant, removed the tenant, removed as a tenant | 解约 | 城镇方解除子区域已有的租用或购买合约, 结束住户身份并收回子区域; 与普通成员移出和撤销租售报价区分。 |
| compensation | 补偿金 | 城镇方与住户解约时支付的补偿金, 涵盖租客和子区域买主, 不表示额外违约罚金。 |

## 风格化

本翻译假定插件是被一个类似 `EarthMC` 的传统城镇服务器使用。你应该根据自己的服务器类型并参照上方的词汇对照表修改翻译来适配服务器玩法，为自己的玩家创造更加沉浸式的体验。

## 下载与更新

本仓库主分支提供当前版本的翻译。每次正式发布都会在 [Releases](https://github.com/YKDZ/Lands-Simplified-Chinese-Translation/releases) 保存当次文件，可按插件版本选择下载。

## 贡献

本仓库实际上是 [维护仓库](https://github.com/YKDZ/Lands-Translation-Maintenance) 的一个投影。若发现遗漏或错误的翻译条目（包括但不限于样式代码缺漏、错字漏字、同词异译等），可以在维护仓库中提交 Issue。

想要参与翻译贡献时，也请在维护仓库中进行，本仓库不应被手动提交修改。

## 支持

本插件文本量较大，若翻译有帮助到你，你可以考虑给这个储存库**上颗星星**。

你也可以点一个 `Watch` 以在翻译更新时收到 Github 的邮件通知。
