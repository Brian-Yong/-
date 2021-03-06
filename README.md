# -
涂鸦【宠物喂⻝器】实战营练习项目
# 宠物喂食器开发计划书

This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.

For more information, please check Tuya Developer Website.

## 一、方案标题

宠物喂食器

## 二、方案应用场景

地点：住所、办公室、宿舍等

功能：帮助不方便亲自投喂宠物的铲屎官们“云养猫狗”，让大家能够在工作、出差等远离宠物期间，无需担心宠物的进食。主要功能如下：

- 根据用户的设定，每天定时、定量喂食
- 手机APP实时控制，选择喂食时间和分量
- 记录历史投喂的时间和分量，方便查阅记录、分析数据
- 喂食器内存储的余粮监测，提醒用户及时补充
- 喂食器上布置开关，训练宠物“自助取餐”

## 三、技术路线

- 总成供电由直流供电电源板执行，12V DC输入或5V USB输入
- 喂食执行机构由H桥直流电机驱动功能板控制减速电机实现
- WiFi通信板（VWXR2）实现离线控制策略（按时、按量投喂），作为远程控制控制失效（断网等）的备份策略
- 尝试开发APP，在线调整投喂时间、分量
- 喂食器将每次投喂的时间、分量作为历史数据上传，方便查阅
- 尝试对历史数据进行学习，结合先验知识，计算出推荐的喂食周期和分量

## 四、开发计划

3月29日前完成

1. 3月9日：参加训练营开营培训
2. 3月10日——3月14日：确定技术路线，利用培训内容，对所需的通信、电机控制等模块程序进行编写
3. 3月15日——3月29日：使用开发套件调试各个模块的程序，并进行整合，实现预期功能
