# GTA5-Stand-Lua-RScript
GTA5 Stand Mod Menu Lua Scripts  
自己编写的自用脚本，把自己常用功能整合一起，部分代码借鉴参考（~~Copy~~）了 Heist Control、Wiri、Lance等等  
自己想要啥功能而且Stand没有或者突然有啥想法了，就会写一下脚本  
新手一个，代码很乱

# 目前功能
### 自我选项
- 自定义最大生命值
- 自定义最大护甲值
- 自定义生命恢复：站立和掩体状态下的恢复程度、恢复速度
- 恢复生命、恢复护甲
- 掩体内快速恢复生命
- 血量低于多少时锁定血量
- 通知
  - 当前生命值和最大生命值
  - 当前护甲值和最大护甲值
- 警察无视
- 所有人无视
- 行动无声

### 武器选项
- 可以射击队友
- 翻滚时自动换弹夹
- 无限弹药（不换弹）
- 锁定最大弹药
- **实体控制枪** 
> 控制瞄准的实体，并且会记录下实体，实现远程控制实体
  - 对于 Entity:
    - 显示和复制实体信息
    - 无敌、冻结、燃烧、设置血量、爆炸
    - 添加地图标记
	- 控制实体 前后左右上下移动和朝向
	- 传送到实体
	- 传送实体 到我前后左右上下，锁定传送在我头上
	- 设置最大实体速度
  - 对于 Ped:
    - 传送到我的载具
	- 移除全部武器、给予武器
	- 一键无敌强化NPC（适用于友方NPC）
	- 控制NPC作战能力
  - 对于 Vehicle：
    - 传送到载具内、传送到驾驶位（强制）
	- 拆下车门、车门开关、车门锁
	- 设置向前的速度
	- 修复载具、爆胎

### 载具选项
- 修复载具无法移动（没啥用）
- 设置和锁定载具灰尘程度
- 防弹轮胎
- 载具引擎快速开启
- 解锁正在进入的载具
- 自动修复前后车窗
- 自动拆下左前门、右前门、所有门
- 个人载具
  - 打开引擎和左车门
  - 开启载具引擎
  - 打开左车门
  - 打开左右车门

### 世界实体选项
- 管理附近的NPC和摄像头（来自Heist Control）
- 管理附近载具
- 管理附近NPC
- 管理附近区域
- **管理任务实体**
- 实体信息枪（查看实体信息）

### 保镖选项
- 保镖直升机

### 保护选项
- 移除爆炸
- 移除粒子效果

### 任务选项
- 分红编辑（除了公寓其余三大抢劫的分红编辑）
- 赌场抢劫
  - 第二面板 自定义可选工作
- 任务生命数修改
- 可调整项
- Local Editor（任务脚本 本地变量编辑）
- Global Editor（全局变量编辑）

### 其它选项
- 零食护甲编辑
- 自动跳到下一条对话（快速跳过对话）
- 请求弹道装甲和火神机枪
- 重型装甲包裹 传送到我
- 无视犯罪
  - 警察无视犯罪（莱斯特）
  - 贿赂当局（CEO）
  - 锁定倒计时

### 玩家选项
- 恶搞选项
  - 生成笼子
  - 生成小查攻击
  - 生成载具内敌人攻击
  - 生成虎鲸
  - 传送所有行人、载具等到他
- 友好选项
  - 没啥用
- 恢复选项
  - 没啥用
  
  
# 最后编辑日期：2022-9-9
