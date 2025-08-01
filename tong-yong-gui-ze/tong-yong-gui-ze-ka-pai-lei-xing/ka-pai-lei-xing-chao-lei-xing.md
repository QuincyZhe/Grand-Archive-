# 卡牌类型 - 超类型

卡牌有时会列出一个超类型，它会修正该卡牌的规则。

超类型依附于卡牌类型；如果卡牌类型被改变，超类型也会随之改变，其结果将是变为没有超类型的默认状态，或是被设定成的任何状态。

{% hint style="info" %}
参见[类型改变](../tong-yong-gui-ze-ka-pai-te-zheng/)
{% endhint %}

1. 独有是一种超类型，它指定了一个玩家在任何时间战场上只能操控1个具有该名称的独有物件。如果一个玩家操控了2个或更多同名的独有物件，该玩家将被迫牺牲掉其中的一些，直到他们只操控1个为止。这会在游戏试图进入下一个游戏状态之前，即在任何效果结算、时机被传递、或游戏将要返回玩家的主要阶段之前进行。即是说，只有在满足了独有物件的规则后，游戏才会继续进行。
   1. 如果战场上有两个物件同名，但只有一个是独有的，则游戏不会要求该玩家牺牲其中一个物件。
2. 礼装是卡牌的一种超类型，它指定了该卡牌必须起始于素材库。
   1. 素材库中卡牌的构筑限制同样适用于礼装；在游戏开始时，一个玩家的素材库中最多只能具有一张特定的礼装。
   2. 所有礼装都具有回忆代价。
   3. 如果一张礼装卡牌将要从任何地方被置入墓场，则改为将其放逐。
   4. 如果一个效果指定要将一张礼装送往手牌、主牌库或回忆区，则它在离开战场上时，会改为返回其拥有者的素材库。
