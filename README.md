# genshin_impact_artifact
适用于hoshino v2的原神随机圣遗物插件

# 指令
- `@bot 圣遗物`: 获取一个随机圣遗物
- `@bot 圣遗物 [指定套装、部位、主属性、副属性]`: 获取一个指定的圣遗物，如：`@bot 圣遗物 魔女火伤杯副攻副攻副暴副暴`

# changelog
### 2020-12-24
- 修复新增的圣遗物图标位置问题

### 2020-12-23
- 更新1.2版本雪山新圣遗物

### 2020-12-18
- 优化属性别名，现在不同种类属性可使用相同别名，满足其中任意一种即认为符合
- 顺带优化原先“生命花”、“攻击羽”的trick判断逻辑
- 支持指定副属性，默认关键词为“副”，可以自行修改

### 2020-12-03
- 重构了圣遗物套装等常量，不再依赖id，修改更方便 (顺带修复了指定的原来id为0的会不生效的问题)
- 适配圣遗物词条出现概率，数据来自 https://bbs.nga.cn/read.php?tid=24286653
- 增加部分别名
- 微调生成的圣遗物图片 (依然不够满意，应该还会调整)

### 2020-11-24
- 支持发送圣遗物图片，部分代码及素材来自 https://github.com/H-K-Y/Genshin_Impact_bot/tree/main/artifact_collect
- 优化了圣遗物图片

### 2020-11-23
- 添加圣遗物图片

### 2020-11-06
- 完成能获取指定套装、部位、主属性的圣遗物

### 2020-11-04
- 完成圣遗物强化

### 2020-11-02
- 完成获取随机圣遗物
