# Crystal Mir 2 Databases

This Repo contains multiple Databases to Crystal Mir 2 
Each folder contains a different Database.

*All databases work with the latest source code*

How to use;

1: Download Mir client & server from https://github.com/suprcode/mir2

2: Run The Server.exe located in the Server folder. Allow it to start then close it down; This is so all initial config files are created.

3: Download preffered database from the appropriate folder

4: Drag and drop all new files into the Server Folder replacing them with the new database.



# Current Databases

- Jev 23/07/20 - Present (Actively updated)
- Daneo1989 27/11/14 - 31/10/15 (No longer updated)
- Jev W/O Archers 21/06/21 - Present (Actively updated)
- Jev W/O Archers & Assassins 21/06/21 - Present (Actively updated)
- Jev W/O Assassins 21/06/21 - Present (Actively updated)
- NightWolf - 13/12/14 - (No longer updated)

# Useful Links

LOMCN - https://www.lomcn.org/

Contributors - https://github.com/Suprcode/mir2-database/graphs/contributors

MirFiles - http://mirfiles.com/

Mir 2 WIKI - http://wiki.mironline.co.uk/Main_Page

Crystal Mir2 Tutorials - https://www.lomcn.org/forum/forums/crystalm2-tutorials.634/

Source code - https://github.com/suprcode/mir2

附：

目前整理出来的待翻译内容在以下路径里，如有发现随时补充

/Jev/Envir/NPCs 该路径下包含所有NPC配置【这里包含大量文本，可以按地图分工作量】

/Jev/Envir/Quests 该路径下包含所有任务配置【这里包含大量文本，可以按地图分工作量】

/Jev/Envir/Events 该路径下包含所有事件触发通知配置【这里文本量不多】

/Jev/Configs/Language.ini 该文件有部分系统警告配置【这里文本量不多】

/Jev/Configs/WorldMap.ini 该文件有一些世界地图区域配置【这里文本量不多】

客户端部分就repo主自己全部承包翻译掉了，基本都是些UI说明之类的文案

还有一些客户端UI里的图片文案需要用LibraryEditor.exe来改图，暂时没打算搞

P.S. 怎么没找到技能面板和技能相关的文案？！算了，让玩家看国服职业百科玩也行，重要的是NPC对话，任务描述和物品描述。物品描述也没找到在哪设置啊！ ——————2023.1.6

# 如何寻找待翻译文本

1. #SAY #ELSESAY 下面一句话通常是要翻译的
2. 什么什么Message "xxxxxxx" Hint  xxxxx部分需要翻译 有LocalMessage
3. 什么什么MESSAGE "xxxxxx" Hint xxxxxx部分需要翻译 有LINEMESSAGE GLOBALMESSAGE
4. @Description下面的文本也是需要翻译的
注意：类似You gained {count} items 这样的文本花括号里面的东西通常是绑定程序变量的，不能动
