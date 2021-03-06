![logo](./_README_/LOGO_900px.jpg) 
# 鸽式未转变者中文汉化 - 一个所有人都能参与的项目
- [鸽式未转变者中文汉化 - 一个所有人都能参与的项目](#鸽式未转变者中文汉化---一个所有人都能参与的项目)
  - [一、项目介绍](#一项目介绍)
  - [二、贡献教程](#二贡献教程)
    - [文件夹的含义](#文件夹的含义)
    - [Bundles文件夹内词条文件格式](#bundles文件夹内词条文件格式)
    - [文件的含义（Menu）](#文件的含义menu)
    - [文件的含义（Player）](#文件的含义player)
  - [三、翻译过程](#三翻译过程)
    - [Example（Localization）](#examplelocalization)
    - [Example（Bundles）](#examplebundles)
  - [四、审核说明](#四审核说明)
  - [五、注意事项](#五注意事项)
  - [六、贡献名单](#六贡献名单)
- [PigeonTypeZhLangInstaller - 鸽式未转变者汉化全自动安装器](#pigeontypezhlanginstaller---鸽式未转变者汉化全自动安装器)
    - [一、制作原因](#一制作原因)
    - [二、使用工具](#二使用工具)
    - [三、原理](#三原理)
## 一、项目介绍
这是一个在Github上的，`所有人都可以参加`的，Unturned翻译项目！
## 二、贡献教程
### 文件夹的含义
| 目录                          | 内容                                          |
| ----------------------------- | --------------------------------------------- |
| /Maps/(关卡名称)/             | 地图的描述文件                                |
| /Localization/Schinese        | UI的语言文件                                  |
| /Localization/Schinese/Editor | UI的语言文件（地图编辑器）                    |
| /Localization/Schinese/Menu   | UI的语言文件（菜单）                          |
| /Localization/Schinese/Server | UI的语言文件（服务器命令 不必翻译）           |
| /Localization/Schinese/Player | UI的语言文件（游玩时的UI）                    |
| /Localization/Schinese/Shared | UI的语言文件（只有一个文件 写着快捷键的解释） |
| /Translations                 | 语言文件（还没翻译）                          |
| /Bundles/Animals              | 动物文件                                      |
| /Bundles/Items                | 物品文件（物品名字/解释）                     |
| /Bundles/NPCs                 | NPC文件（NPC对话内容/NPC名字）                |
| /Bundles/Objects              | 求大佬解释                                    |
| /Bundles/Vehicles             | 车辆文件                                      |
### Bundles文件夹内词条文件格式
| 目录                         | 内容       |
| ---------------------------- | ---------- |
| /Bundles/Animals/(名字)      | /          |
| /Bundles/Items/(类型)/(名字) | /          |
| /Bundles/NPCs/(类型)/(名字)  | /          |
| /Bundles/Objects             | 求大佬解释 |
| /Bundles/Vehicles/(名字)     | /          |
### 文件的含义（Menu）
| 目录                                      | 文件                            | 内容                                                |
| ----------------------------------------- | ------------------------------- | --------------------------------------------------- |
| /Localization/Schinese/Menu               | MenuDashboard.dat               | 主界面菜单/各种被踢出原因                           |
| /Localization/Schinese/Menu               | MenuLoading.dat                 | 游戏刚打开加载 服务器/单人模式进入加载              |
| /Localization/Schinese/Menu               | MenuPause.dat                   | 游戏暂停的界面                                      |
| /Localization/Schinese/Menu               | MenuTips.dat                    | 游戏刚打开加载/服务器/单人模式加载时显示的提示      |
| /Localization/Schinese/Menu               | MenuTitle.dat                   | 游戏制作者栏+你与全世界的差别                       |
| /Localization/Schinese/Menu/Configuration | MenuConfiguration.dat           | 设置主体                                            |
| /Localization/Schinese/Menu/Configuration | MenuConfigurationControls.dat   | 设置-控制                                           |
| /Localization/Schinese/Menu/Configuration | MenuConfigurationDisplay.dat    | 设置-显示                                           |
| /Localization/Schinese/Menu/Configuration | MenuConfigurationGraphics.dat   | 设置-画质                                           |
| /Localization/Schinese/Menu/Configuration | MenuConfigurationOptions.dat    | 设置-游戏设置                                       |
| /Localization/Schinese/Menu/Play          | MenuPlay.dat                    | 游玩主界面                                          |
| /Localization/Schinese/Menu/Play          | MenuPlayConfig.dat              | 单人游戏高级设置                                    |
| /Localization/Schinese/Menu/Play          | MenuPlayConnect.dat             | 连接页面（直接输入IP地址连接服务器的）              |
| /Localization/Schinese/Menu/Play          | MenuPlayLobbies.dat             | 拉Steam好友的主页                                   |
| /Localization/Schinese/Menu/Play          | MenuPlayMatchmaking.dat         | 不知，似乎是根据游戏上地图找服务器                  |
| /Localization/Schinese/Menu/Play          | MenuPlayServerInfo.dat          | 服务器详细页面                                      |
| /Localization/Schinese/Menu/Play          | MenuPlayServers.dat             | 寻找服务器页面                                      |
| /Localization/Schinese/Menu/Play          | MenuPlayServerInfo.dat          | 服务器详细页面                                      |
| /Localization/Schinese/Menu/Play          | MenuPlaySingleplayer.dat        | 单人游戏页面                                        |
| /Localization/Schinese/Menu/Play          | MenuServerPassword.dat          | 当服务器有密码保护让你输入密码的界面                |
| /Localization/Schinese/Menu/Survivors     | ItemStoreMenu.dat               | 物品商店界面（就是皮肤）                            |
| /Localization/Schinese/Menu/Survivors     | MenuSurvivors.dat               | 个人设置的跳转界面                                  |
| /Localization/Schinese/Menu/Survivors     | MenuSurvivorsAppearance.dat     | 外观（头发等颜色的设置）                            |
| /Localization/Schinese/Menu/Survivors     | MenuSurvivorsCharacter.dat      | 名称&职业选择界面                                   |
| /Localization/Schinese/Menu/Survivors     | MenuSurvivorsClothing.dat       | 设置皮肤&你找到一个物品！&皮肤等级规定&合成皮肤界面 |
| /Localization/Schinese/Menu/Survivors     | MenuSurvivorsClothingBox.dat    | 开箱显示界面                                        |
| /Localization/Schinese/Menu/Survivors     | MenuSurvivorsClothingDelete.dat | 删皮肤界面（SALVAGE & DELETE）                      |
| /Localization/Schinese/Menu/Survivors     | MenuSurvivorsClothingItem.dat   | 点进皮肤的详细界面（比如use）                       |
| /Localization/Schinese/Menu/Survivors     | MenuSurvivorsGroup.dat          | 组                                                  |
| /Localization/Schinese/Menu/Workshop      | *                               | 创意工坊界面 （鸽子不懂技术层面的内容 求大佬解释）  |
### 文件的含义（Player）
| 目录                                  | 文件                         | 内容                                                                 |
| ------------------------------------- | ---------------------------- | -------------------------------------------------------------------- |
| /Localization/Schinese/Player         | PlayerPause.dat              | 玩家暂停游戏                                                         |
| /Localization/Schinese/Player         | PlayerNPCVendor.dat          | NPC商店                                                              |
| /Localization/Schinese/Player         | PlayerNPCQuest.dat           | NPC任务&数据解释&UI                                                  |
| /Localization/Schinese/Player         | PlayerLife.dat               | 名字为Life，指游玩时各种提示内容（如杀死僵尸/满月降临/各种交互界面） |
| /Localization/Schinese/Player         | PlayerDeath.dat              | 玩家死亡时的界面/死亡提示                                            |
| /Localization/Schinese/Player         | PlayerDashboardSkills.dat    | 玩家TabUI - 技能界面                                                 |
| /Localization/Schinese/Player         | PlayerDashboardInventory.dat | 玩家TabUI - 物品种类/物品栏交互UI/物品稀有度                         |
| /Localization/Schinese/Player         | PlayerDashboardCrafting.dat  | 玩家TabUI - 合成界面                                                 |
| /Localization/Schinese/Player         | PlayerDashboard.dat          | 玩家TabUI - 上方的按钮（物品栏/合成/技能/信息）                      |
| /Localization/Schinese/Player         | PlayerBrowserRequest.dat     | 当服务器邀请你打开网页时，弹出的提示信息                             |
| /Localization/Schinese/Player         | PlayerBarricadeMannequin.dat | 人偶的UI                                                             |
| /Localization/Schinese/Player         | PlayerBarricadeSign.dat      | 告示牌的UI                                                           |
| /Localization/Schinese/Player         | PlayerBarricadeStereo.dat    | 收音机的UI                                                           |
| /Localization/Schinese/Player/Useable | PlayerUseableGun.dat         | 玩家使用远程武器信息栏                                               |
## 三、翻译过程
### Example（Localization）
```
Test1 English
Test2 English
Test3 English {1}
Test4 English {1} {2} {3}
Test5 English{1}{2}{3}
```
- `Test1~4`为开发者设置的名字，绝对不能更改！不然会导致Unturned无法识别，会变成`#TEST1`的（就像翻译文件没更新，~~新版Unturned的退出按钮就会变成#QUIT_BUTTON~~（在3.22.11.0的更新中，会显示原版英文。）
- `English`才是翻译文本，你只能修改这个！
- `{1}` 为替换符，绝对要格式对，不然会导致UI不显示问题！`{}`是英文！`{1}`中的数字也不能更改.
- `{1} {2} {3}` 为多个替换符也不能更改，顶多因为翻译换一下顺序！
### Example（Bundles）
- 假如我找`碎心人`枪械的语言文件，那就要去`Items`文件夹，找到`Guns`列表，找到`Heartbreaker`文件夹，打开`Heartbreaker`文件夹会有两个文件（`Heartbreaker.dat` / `English.dat`）
- 打开`English.dat`，你能看到下面的内容（有些并没有"Description"，就比如animal/bear）
```
Name Heartbreaker
Description Belgian assault rifle chambered in Military ammunition.
```
- Name (名字)
- Description (描述)
- 翻译后把`English.dat`改成`Schinese.dat`，删除`Heartbreaker.dat` 大功告成，然后提交PR。
## 四、审核说明
- 在当日0:00~17:00提交PR当日18:00后审核。
- 在当日17:00~20:00提交PR当日21:00后审核。
- 在当日22:00之后提交PR次日18:00后审核。
- 除非有特殊情况，不然都是当日/次日审核。
## 五、注意事项
- 在提交PR时务必要把版本对上号！别把旧版推到新版上
- 如果你不会pr，可以b站私信我...（https://space.bilibili.com/1372244620）
## 六、贡献名单
- 一个小鸽子(https://github.com/YigeXiaogeziAwa) | Github
- ruanwei8110 | 场外援助
- 渣白 | 场外援助
- ilunp(https://github.com/ilunp) | Github

# PigeonTypeZhLangInstaller - 鸽式未转变者汉化全自动安装器
### 一、制作原因
- 安装汉化太烦了，于是出现这样全自动的安装脚本
### 二、使用工具
> 7z 命令行工具
### 三、原理
- 先检测patch目录（放汉化文件的地方）下面的Bundles等等文件夹是否存在，不存在关闭，存在继续。
- 使用`reg query`功能来取注册表`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall\Steam App 304930`路径下的`InstallLocation`项中的值，把得到的值存入`%InstallLocation%`变量中。
- 取到`InstallLocation`的值后 使用`if not exist`检验文件夹是否存在（如果报错 也会显示不存在）
- 使用`robocopy`把patch目录下文件统统复制到%InstallLocation%下。
