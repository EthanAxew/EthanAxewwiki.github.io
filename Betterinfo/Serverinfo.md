# 查询服务器信息

------

![默认](https://bu.dusays.com/2024/08/11/66b8a7cb49a18.png)

### 一.关于物品

默认查询物品为指南针,暂不能更改,如需更改请联系作者！

### 二.关于配置文件

1.默认 查询天气,难度,死亡不掉落,生物破坏,在线人数.

2.玩家可以自定义文字,全部支持PAPI变量

3.关于config.yml设置

```yml
#是否显示分割线
divider:
  #第一行分割线
  divider1: true
  #第二行分割线
  divider2: true
  #第三行分割线
  divider3: true
#此处为是否显示自带显示信息
```

```yml
info:
  #是否显示当前天气消息
  weatherinfo: true
  #是否显示游戏难度消息
  difficultinfo: true
  #是否显示死亡掉落/不掉落消息
  keepinfo: true
  #是否显示开启防爆/关闭防爆
  mobfireinfo: true
  #是否显示当前世界在线玩家数量
  playerlistinfo: true
```

```yml
custom:
  #是否开启
  enable : true
  messages:
    - "§c用户自定义消息可多行"
    - "§c用户自定义消息可多行"
    - "§c用户自定义消息可多行"
```

默认全部开启

------

### 三.关于语言文件

1.服主可以自定义消息显示,支持PAPI变量

```
#第一行分割线
info1: "-----§bworld§f----"
weatherinfo: "§b当前天气:"
difficultyinfo: "§b当前难度:"
gameruleinfo:
  keep: "§b死亡掉落:"
  mob: "§b生物破坏:"
#第二行分割线
info2: "-----§bServer§f----"
playerlist: "§b当前世界在线人数:"
#第三行分割线
info3: "-------------------"
difficulty:
  peaceful: "§6和平"
  easy: "§6简单"
  normal: "§6普通"
  hard: "§6困难"
weather:
  sun: "§6晴天"
  rain: "§6雨天"
  thunder: "§6雷雨天"
info:
  true: "§6开启"
  false: "§6关闭"
player:
  name: "§6玩家"
#-------------------------------------
```

用户可以随意设置语言文件,注意格式！

| [<<上一页--简介](Betterinfo/info.md)<div style="width:200px"> | [下一页--玩家加入消息>>](Betterinfo/Playerjoin.md)<div style="width:200px"> |
| ------------------------------------------------------------ | -----------------------------------------------------------: |

