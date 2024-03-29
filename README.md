# 声明

该说明文件仅针对当前时间(2024年3月29日)

灵感来自TGLTN的直播切片

# 功能

用日常软件LOGO替换PUBG对战记录中每个队伍临时LOGO（每局队伍都会"随机"的数字编号）

***仅针对试试进行的对局，录像不会生效***

# 文件（夹）作用

```
Observer
 | TeamIcon             (替换显示的图标)
 | TeamIcon_national    (原作者的旗帜图标)
 L Teaminfo.csv         (告诉PUBG每个队伍编号对应哪个图标)
```

# 使用方法（描述）

1. 按下Win+R，输入'%appdata%'（不要输入单引号）
2. 返回上层目录（例：C:\Users\你的用户名\AppData）
3. 按顺序进入文件夹：Local -> TslGame -> Saved
4. 将Observer文件夹放进来（C:\Users\你的用户名\AppData\Local\TslGame\Saved）
5. 重启PUBG即可成功

# 使用方法（视频）

[Bilibili-索姆斯小鼠](https://www.bilibili.com/video/BV1fz421Z7zj/)

# 原理（猜测）

可能是打联赛时OB视角需要显示每个联赛队伍的LOGO，所以蓝洞设计了这种方式来显示队伍图标。

**这只是猜测，如果猜测错误也请指出，一起学习。**

# 制作方法来源

[Github-Ciseur/ciz-pubg-killfeed-flags](https://github.com/Ciseur/ciz-pubg-killfeed-flags) 感谢作者
