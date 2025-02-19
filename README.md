# 无光之海汉化

项目延续自：
>https://github.com/InstantComet/SunlessSea?tab=readme-ov-file


赞美前人大佬，正是仰赖十年来各位船长的接力，大家才能无障碍玩到这款游戏


## 修改存档数值

1. 首先打开游戏，开始新游戏，手动存一个档

2. windows前往存档JSON文件：

```
C:\Users\{你的windows用户名}\AppData\LocalLow\Failbetter Games\Sunless Sea\saves\{你的存档名}.json
```
找不到的话从C盘里找AppData目录往下找

3. 找到后用Nodepad或者VSCode之类的文本/代码编辑器打开，然后搜索以下数字，并修改数值：

102894 = Iron 铁
102895 = Mirrors 镜子
102896 = Veils 面纱
102897 = Hearts 红心
102898 = Pages 纸页

**修改对应项所在的Json object里的Level属性，Level是多少游戏中的数值就是多少**


起始一般为25，改到50基本可以横着走了，追求游戏沉浸感建议改到30到40


比如铁对应的Json object大概长这样：
```
{"Name":null,
"EquippedPossession":null,
"Relationships":[],
"XP":0,
"EffectiveLevelModifier":1,
"TargetQuality":null,
"TargetLevel":null,
"CompletionMessage":null,
"Level":50, // <- 改这里！！
"AssociatedQuality":null,
"AssociatedQualityId":102894,
"QualityName":null,
"QualityDescription":null,
"QualityImage":null,
"QualityNature":null,
"QualityCategory":null,
"QualityAllowedOn":null,
"Id":0},
```

其他重要资源ID：

102025 = Terror （恐惧值）
102026 = Supplies （补给）
102027 = Fuel （燃料）
102028 = Echoes （回声/钱）
102029 = Hull （船壳血量）
102030 = Crew （船员数量）
102032 = Secret
102328 = Objective: An Admiralty Commission - check wki
102973 = Something Awaits You - use the wiki to deciede what to change the "Level": to
108545 = Fragments
109124 = Acquaintance: Sojourning with the Sisters - check wki
109775 = Deliveries from the Salt Lions - check wki
110310 = Favours: A Drop of Darkness - check wki
110360 = Another Day: Time, the Healer
110364 = A New Recruit
110370 = Objective: Collecting Cargo for the Cheery Man - check wki
112704 = Principles' End: Principality - check wki
115051 = Memoirs: Beginner's Luck - this one you would have to delete the whole code block it is in to remove the attribute
116006 = Lineage: Captains Lost - set to 1+ to unlock The Labyrinth of Tigers in London
117204 = Menaces: Yearning, Burning （威胁，一般来自见到阳光后，累积多了会死）


其他通过修改文件直接获得高级武器，船官等，请参考：
https://steamcommunity.com/sharedfiles/filedetails/?id=588725254


无光之海wiki百科以及全部海图：
https://sunlesssea.fandom.com/wiki/Map


另外建议打个给船加速的Mod，之前安装过找不见了，找到了会附在这里


## 以下是原汉化项目作者的使用教程，亲测可用



~~**FBG在2023年1月26日进行的更新(版本2.2.11.3212)摧毁了界面汉化。因此，本项目不再进行活跃维护（记仇）**~~
# **本项目仅包含文本汉化，要获得界面汉化体验，请参考[tinygrox](https://github.com/tinygrox)的项目[SunlessSeaCN](https://github.com/tinygrox/SunlessSeaCN)**
<br />
<br />

![image](https://raw.githubusercontent.com/InstantComet/images/main/img/20221201030329_1.jpg)

# 使用方法：

### 1. 参照[SunlessSeaCN](https://github.com/tinygrox/SunlessSeaCN)中的说明，完成UI汉化

### 2. 下载[Sunless_sea_CN_reborn.zip](https://github.com/InstantComet/SunlessSea/releases/download/24.12.10/Sunless_sea_CN_reborn.zip)，解压备用  [OneDrive网盘分流](https://42witch-my.sharepoint.com/:u:/g/personal/comet_42witch_onmicrosoft_com/EVtgS1os_iNPsQ6v-bYMIBYBI2wSq-DDi8jv89iK3L9sSA?e=0UWN8F)

### 3. 启动游戏，以让其生成需要的文件，然后关闭游戏 （非必需，进行UI汉化的过程应该已经进行过一次启动）

### 4. 解压Sunless_sea_CN_reborn.zip，你应当能看到addon以及images两个文件夹

### 5. 将这两个文件夹复制到以下的位置：（请直接按Windows+R，粘贴以下内容到框内，然后敲击回车）
```
%AppData%\..\LocalLow\Failbetter Games\Sunless Sea
```

### 6. 完成
***

Epic, GOG:可用

项目延续自

>https://github.com/diskrubbish/Sunless_Sea_Chinese_Translation_Mod_Re

赞美每一位大佬

目前在最新版的addon文件夹中，有已汉化的沦敦仓库mod以及一个包含汉化组译名勘误/注释表的mod，如果不喜欢这些mod只需在下载后直接删除addon文件夹即可

注意本汉化补丁为了实现完全汉化，替换了游戏的资源文件，对于没有购买潜艇DLC(Zubmariner DLC)的玩家，请不要替换resources.assets文件

***
个人的推荐mod:


## 安装方式见每个mod自己的指南，此处不提供任何技术支持

~~London Warehouse（在沦敦为玩家提供一个仓库，本mod已汉化，并整合进本汉化补丁）
https://www.nexusmods.com/sunlesssea/mods/18~~

Cloud Saving Fix（修复点击“继续”时，游戏画面右上1/4是海，然后卡死的BUG）
https://www.nexusmods.com/sunlesssea/mods/40

Immersive Log Book（ssk风格的日志显示）
https://www.nexusmods.com/sunlesssea/mods/34

Fragment Rollover Fix（修复碎片转换成秘密时会吞掉多余碎片的问题）
https://www.nexusmods.com/sunlesssea/mods/36
