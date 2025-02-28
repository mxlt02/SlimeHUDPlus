# SlimeHUDPlus

此分支的主要区别:
1. 默认不启用, 而是权限
2. 添加了多种命令, 更灵活
3. 深度汉化
与主分支原版自动同步更新,不会落后与原版!
---
可以给玩家或者VIP的命令(默认OP拥有权限)

/slimehud toggle 切换显示状态 | 权限节点 slimehud.togglewaila

/slimehud enable 开启自己的显示状态 | 权限节点 slimehud.togglewaila

/slimehud disable 关闭自己的显示状态 | 权限节点 slimehud.togglewaila


管理员命令,支持控制台(默认OP拥有权限)

/slimehud enable 玩家名 开启其他玩家显示状态 | 权限节点   slimehud.admin.togglewaila

/slimehud disable 玩家名 关闭其他玩家的显示状态 | 权限节点   slimehud.admin.togglewaila


---
详细教程请访问 https://www.mcbbs.net/thread-1377794-1-1.html

注意: 本人并非作者, 此插件由SchnTgaiSpock https://github.com/SchnTgaiSpock/SlimeHUD 开发, 由鬼斩汉化 https://github.com/SlimefunGuguProject/SlimeHUD , 本人在次基础上画蛇添足了一下, 要感谢去感谢作者和鬼斩去, 我做的微不足道!

The main differences in this branch are:
1. The default value is not enabled, but permission
2. Multiple commands are added for flexibility
3. Deep Chinese

Note: I am not the author, this plugin developed by SchnTgaiSpock https://github.com/SchnTgaiSpock/SlimeHUD , by 鬼斩 localization, https://github.com/SlimefunGuguProject/SlimeHUD, to thank to thank the author SchnTgaiSpock and 鬼斩, I do insignificant!

---


添加了 Slimefun 方块的 WAILA (我在看什么) 显示功能。  
你可以直接获得你看向的方块的名称，不需要打开菜单，或是破坏方块。  

可以在`config.yml`中设置使用BossBar或ActionBar显示。  
额外的能源/货运网络信息也可以设置开启或关闭。

玩家可以使用指令 `/slimehud toggle` 来切换 WAILA 的开关。

## 下载

点击这里下载 SlimeHUDPlus: [下载 SlimeHUD]([https://builds.guizhanss.net/SlimefunGuguProject/SlimeHUD/master](https://github.com/mxlt02/SlimeHUDPlus/releases))


## 预览

### BossBar 版本

<https://user-images.githubusercontent.com/101147426/180625208-4713a843-e856-475e-ba83-95b5a61786f8.mp4>

### ActionBar 版本

https://user-images.githubusercontent.com/101147426/180625211-cbcfd01d-d418-4e6c-a8ab-55d938d7840e.mp4

## 限制

- Minecraft 仅有7种颜色的BossBar，而聊天文字颜色却有16种。

## 需要

- Spigot 或衍生服务端
- Slimefun

## Credits

*InfinityLib* by Mooy1
*Lombok* by Project Lombok

## bStats

![bStats](https://bstats.org/signatures/bukkit/SlimeHUDPlus.svg)
