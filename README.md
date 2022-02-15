# ChineseNewYear
A minecraft mod draft including Chinese lunar calendar, astronomical observation and additional agriculture.
一个与农历历法、天文观测和补充的农业玩法为特点的Minecraft模组，目前仅在构想阶段，有兴趣的可加Q：553724286。


# 大致的构想：
+ 每一个存档根据种子生成随机的一组天文数据，包括地图所在星球的地轴、自转周期、公转周期、月球（唯一的一颗卫星）的公转周期和玩家所处的纬度（假设行星非常巨大，整个存档都在同一个维度上）。
+ 根据存档种子生成随机的星图用于玩家的天文观测，太阳和月亮的贴图会根据天文数据修改显示位置；月相的贴图不作更精细的修改，但是周期不再是默认设置的8天。
+ 按照时间推移产生季节变化，调整不同生物群系的环境参数和实体行为，如有极昼极夜日光条件也随之更改。
+ 特定的星象和具体的节气会有相应的农业事件，或增加产量、或加速生长、或产生特定实体。

# 玩法设计和游戏难度
+ 存在通关的概念，即完全推算出准确的历法，通关的具体方式是完成一系列符合历法要求的天文建筑（比较初级的一个建筑例如日晷）。
+ 太阳位置、月球位置、月相和星图不能通过GUI或者是其他道具获得，完全需要通过玩家在空间中借助方向实现观测，mod也不会提供辅助计算工具。
+ 在完成通关任务之后会获得一种材料，可用于合成行星发动机，玩家可以通过消耗大量能源驱动行星发动机朝某个角度推进，实现调整地图天文参数的目的，例如实现永久白昼或者黑夜，或者是更快、更慢的昼夜更替。

