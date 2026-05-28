# XIVCombo Expanded CN v2 [![Build](https://github.com/MKhayle/XIVComboExpanded/actions/workflows/build.yml/badge.svg)](https://github.com/MKhayle/XIVComboExpanded/actions/workflows/build.yml)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R2F1EYP)

这个插件可以把连击技能和互斥技能整合到同一个按钮上。

## Dawntrail 更新说明
目前各职业在 90 级及以下应该都能正常工作。90 级以上不做保证，部分功能可能会失效。如果你遇到问题，请在这里反馈。

## 关于项目
XIVCombo 是一个用于实现“一键连击”的插件，同时也提供多种互斥技能整合与便利性替换功能。

![ffxiv_dx11_HYu4aLT75g](https://github.com/user-attachments/assets/9ebf9a61-c093-4300-958b-4abde9188484)

![ffxiv_dx11_BrmTBN2FuL](https://github.com/user-attachments/assets/734cd1ff-9159-4862-9876-8485257dd222)

对于部分职业，这能大幅节省热键栏空间（说的就是你，`DRG`）。而对大多数职业来说，它可以减少很多机械重复、但实际上没必要拆成多个按键去按的操作负担。

## 安装方法
* 将 `https://raw.githubusercontent.com/lichi7887/MyDalamudPlugins/master/pluginmaster.json` 添加到 `/xlsettings` 的第三方仓库列表中，以便获取这个插件。
* 在游戏内输入 `/xlplugins` 打开插件安装器和更新器。
* 首次安装时应会弹出初始化设置窗口。

## 游戏内使用方式
* 输入 `/pcombo` 打开图形界面，编辑已启用的连击替换项。
* 将对应名称的技能从技能列表拖到热键栏上即可使用。
* 例如，如果你想使用 `DRK` 的 `Souleater` 连击，先勾选对应选项，再把 `Souleater` 放到热键栏上。它会自动变成 `Hard Slash`。
* 每个连击项附带的说明通常足以告诉你，应该把哪个技能放到热键栏上。

## 示例
![](https://github.com/MKhayle/xivcomboplugin/raw/master/res/souleater_combo.gif)
![](https://github.com/MKhayle/xivcomboplugin/raw/master/res/hypercharge_heat_blast.gif)
![](https://github.com/MKhayle/xivcomboplugin/raw/master/res/eno_swap.gif)

## 致谢
这个 attick 的 XIVCombo 分支最初由 [daemitus](https://github.com/daemitus) 开发。我在他不再游玩本游戏后接手维护。
为了保证迁移过程平滑，在 daemitus 的配合下，仓库地址保持不变。
感谢 Meli 提供最初的起点，当然也要感谢 goat，没有他这些都无法实现。
lichi7887 为本插件适配了《最终幻想 XIV》国服客户端。
