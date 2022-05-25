# 東方月灵传 训练营

## 一、 这是什么
这是一张星际争霸游戏大厅自定义地图的拓展依赖

> battlenet:://starcraft/map/5/109989
>
> 地图核心搬运自亚服地图“东方月灵传(Ver.1.992)”
>
> 感谢sym、岛风、奇缘对现版本的汉化支持。
>
> 感谢谐q、辉夜对之前版本汉化做出的贡献。

## 二、 如何使用
- 将脚本文件打包成mod依赖
- 在mapinit事件中引用initaddons()

## 三、 注意事项
原地图指国服版本，即上文提到的地图

本拓展全部使用galaxy语言编写，由于个人习惯问题可能注释有亿点多（

本拓展重写了很多原图的触发器

最后，本拓展仅供学习与交流

## 四、计划
### 1.指令系统
- [x] -summon heroid player(1 for ally,0 for enemy)
- [x] -testCH 测试次数 暴击点数
  - 测试暴击
- [x] -testRandomFixed 次数
  - 测试随机数
- [ ] -effect effect_name
- [ ] -behavior behavior_name

### 2.主菜单
- [ ] 支持创建英雄，可以选择创建的阵营
- [ ] 支持给予选择单位无敌、无cd无限蓝量
- [ ] 支持获取单位视野
- [ ] 支持添加木偶
- [ ] 支持开启伤害计算
- [ ] 支持天赋选择，可以给予选择单位天赋对应效果
- [ ] 如果英雄有多套技能，支持切换技能组合
- [ ] 支持切换天赋，限制天赋树

### 3.转换为依赖