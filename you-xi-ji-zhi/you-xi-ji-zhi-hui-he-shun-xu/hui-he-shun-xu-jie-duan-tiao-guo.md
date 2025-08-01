# 回合顺序 - 阶段跳过

如果一个效果或条件将要跳过游戏中的一个阶段，则该阶段不会发生。任何与该阶段相关联的回合行动或效果都不会发生，并且如果玩家本应在该阶段获得时机，他们也绝不会获得时机来做出玩家行动。

阶段可以被跳过多次。如果发生此情况，如有必要，那些阶段将被分别跳过，即使是跨越多个回合。

被跳过的阶段不会进行任何阶段结束效果或回合行动。

{% hint style="info" %}
例如，如果一个玩家的结束阶段被跳过，则任何本应在结束阶段发生的事情（例如回合结束效果）都不会发生。如果一个等待中的触发指定了“下一个结束阶段”，它将会在下一个玩家的结束阶段发生。如果一个等待中的触发改为指定“你的下一个结束阶段”，它将会在你下一个回合的结束阶段发生。
{% endhint %}
