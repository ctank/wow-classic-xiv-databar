# wow-classic-xiv-databar



错误信息:

```
1x [ADDON_ACTION_BLOCKED] 插件 'XIV_Databar' 尝试调用保护功能 'XIV_Databar:ClearAllPoints()'。
!BugGrabber\BugGrabber.lua:519: in function <!BugGrabber\BugGrabber.lua:519>
[C]: in function `ClearAllPoints'
XIV_Databar\core.lua:298: in function `Refresh'
XIV_Databar\core.lua:427: in function <XIV_Databar\core.lua:423>
[C]: ?
...nfig-3.0\AceConfigDialog-3.0\AceConfigDialog-3.0-78.lua:51: in function <...nfig-3.0\AceConfigDialog-3.0\AceConfigDialog-3.0.lua:49>
...nfig-3.0\AceConfigDialog-3.0\AceConfigDialog-3.0-78.lua:843: in function <...nfig-3.0\AceConfigDialog-3.0\AceConfigDialog-3.0.lua:664>
[C]: ?
...Ons\ClassicThreatMeter\lib\AceGUI-3.0\AceGUI-3.0-39.lua:72: in function <...Ons\ClassicThreatMeter\lib\AceGUI-3.0\AceGUI-3.0.lua:70>
...Ons\ClassicThreatMeter\lib\AceGUI-3.0\AceGUI-3.0-39.lua:287: in function `Fire'
...ter\lib\AceGUI-3.0-39\widgets\AceGUIWidget-DropDown.lua:442: in function <...ter\lib\AceGUI-3.0\widgets\AceGUIWidget-DropDown.lua:433>
[C]: ?
...Ons\ClassicThreatMeter\lib\AceGUI-3.0\AceGUI-3.0-39.lua:72: in function <...Ons\ClassicThreatMeter\lib\AceGUI-3.0\AceGUI-3.0.lua:70>
...Ons\ClassicThreatMeter\lib\AceGUI-3.0\AceGUI-3.0-39.lua:287: in function `Fire'
...b\AceGUI-3.0-39\widgets\AceGUIWidget-DropDown-Items.lua:351: in function <...b\AceGUI-3.0\widgets\AceGUIWidget-DropDown-Items.lua:341>

Locals:
InCombatSkipped 

http://nga.178.com/read.php?&tid=18329365&pid=361173299&to=1
```



BUG整理:

1. 公会图标移过去 只显示成员列表，而无法点击打开公会面板
2. 不显示系统信息，在模块里已经开启了
3. 启动金钱模块, 系统信息模块就失效的问题

