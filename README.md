# Lands Simplified Chinese Translation

先前曾咨询过插件作者，发现他们采用的翻译维护平台真的很难用，故自行开设储存库维护简体中文翻译。

纯手动翻译，不含 AI 翻译等。

当前对应的插件版本：[6.46.7](https://www.spigotmc.org/resources/lands-%E2%AD%95-land-claim-plugin-%E2%9C%85-grief-prevention-protection-gui-management-nations-wars-1-20-support.53313/updates)

## 安装使用

如果你从未修改过插件的配置文件，你大可以将所有文件直接放入 plugins/Lands 中并重启服务器以自动同步可能的更新。

如果你曾经修改过插件的配置文件，建议你只将 Language/zh-CN_gui.yml 以及 Language/zh-CN.yml 放入对应文件夹中，并将另外的配置文件作为对照，修改你目前的配置文件，以防丢失任何信息。

别忘记将 config.yml 中的 general.language 键修改为 zh-CN。

## 翻译内容

```
Language/en-US_gui.yml -> Language/zh-CN_gui.yml
Language/en-US.yml -> Language/zh-CN.yml
categories.yml
levels.yml
roles.yml
```

仅翻译了可以显示在游戏内的文本，没有翻译配置文件注释等不重要的文本（因为量大且难以维护）。

其中与管理员相关的命令和菜单文本的翻译可能比针对玩家的文本和菜单的翻译要粗糙，因为原插件文本就很模糊。

## 翻译风格

本翻译融合了部分个人风格，在此处声明，以便识别：

- 所有的标点符号皆为英文半角标点（因为在 Minecraft 游戏内使用官方中文字体时，中文全角标点给人的观感较差，欠缺美观）
- 不使用**您**字

## 词汇对照

本插件使用了数个赋予了特殊含义的名词和动词，它们的翻译可能随着服务器的玩法和性质等而改变，故提供名词对照表，方便使用 VSCode 等编辑器的批量修改功能快速地进行匹配替换以满足各类服务器的需求。

```
Nation -> 联邦
Capital -> 首都
Land -> 城镇
Area -> 子区域
Camp -> 露营地
Wilderness -> 荒野

Role -> 职位

Tenant -> 租客

Claim -> 
n. 领土
v. 占领

Unclaim -> 解除占领

Natural Flags / Settings -> 环境设置
Role Flags / Settings -> 职位设置

Bank -> 金库
Upkeep -> 维护费
Taxes -> 税费

Relation -> 外交关系
Ally -> 盟友
Enemy -> 政敌
Neutral -> 中立
```

## 风格化

本翻译假定插件是被一个类似 EarthMC 的传统城镇服务器使用。你应该根据自己的服务器类型并参照上方的词汇对照表修改翻译来适配服务器玩法，为自己的玩家创造更加沉浸式的体验。

## 更新

本储存库仅储存最新版本的插件翻译，不归档老版本。

本储存库将随着插件更新而及时同步翻译（可能有几天的延迟）。

使用 Lands 插件自带的翻译文件更新功能进行更新并翻译新增的文本，这可能导致各个翻译键在文件中的位置与原版英文翻译不同。这不会影响翻译文件的使用。

## 贡献

若发现遗漏或错误的翻译条目，请在 Issues 处指出。

## 支持

本插件文本量较大，若翻译有帮助到你，你可以考虑给这个储存库上颗星星，抑或是在 [爱发电](https://afdian.net/a/ForestRealm) 赞助我。