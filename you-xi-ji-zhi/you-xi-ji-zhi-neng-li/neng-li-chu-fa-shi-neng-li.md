# 能力 - 触发式能力

触发式能力是玩家在状态检测期间，因某个游戏事件或条件的满足（即“触发”）而被置于效果堆叠上的能力。触发式能力的结算会导致在触发之后指定的效果生效。其效果中使用“可以”一词的触发式能力是一个例外；操控该触发的玩家通常被给予一个选项，来选择在结算期间将要发生哪个效果（或是否发生效果）。

触发式能力通常使用“在”（At）、“当”（When）或“每当”（Whenever）这样的词来指定一个触发事件，其后（可选地）跟着一个介入条件或“如果（if）”语句，并最终跟着一个效果。触发式能力可以是关键词化的，其条件和触发事件被缩写在关键词之内，但通常会缺少任何介入条件。因此，只要满足了与关键词绑定的条件，关键词化的触发式能力便会触发，无论该能力的任何效果中是否列出了任何进一步的指定条件。

1. 触发式能力通常的措辞为“\[触发]，\[条件]，\[效果]”。一个\[条件]可以进一步修正主触发，并通常使用诸如“如果”（If）或“除非”（Unless）这样的词。对于非关键词化的触发式能力，如果除了触发事件外，此条件未被满足，则该能力将触发失败；它绝不会被置于效果堆叠上等待结算。此外，如果这样一个条件被指定并被满足，使得该触发进入了效果堆叠，但在结算期间该条件又变得未满足，则该触发不会结算。
2. 一些触发式能力是条件性触发能力，它会描述一个必须被满足的条件，其后跟着一个当该触发条件被满足时将被置于效果堆叠上的效果。条件性触发能力通常使用诸如“参战时”这样的关键词，且其措辞为“\[触发/触发条件]：\[效果]”。这些条件通常出现在常见的事件或不复杂的条件中，例如参战时、攻击时或死亡时。

{% hint style="info" %}
例如，Lorraine, Wandering Warrior 具有“参战时：从你的素材库具现一张回忆代价为0的武器牌。”此处的“参战时”便是一个条件性触发能力，它会在触发条件被满足时，将“从你的素材库具现一张回忆代价为0的武器牌”这个效果置于效果堆叠上。

![](<../../.gitbook/assets/image (4) (1).png>)
{% endhint %}

3. 对于每种情况，触发或触发条件都必须被满足，该触发才能进入效果堆叠。

如果一个触发式能力要求一个玩家选择一个模式，该模式在该能力进入效果堆叠时被选择，且在位于其中时不能被更改。如果没有合规的模式可供选择，该能力将会失效。类似地，如果一个触发式能力要求一个目标，该目标必须在它被置于效果堆叠上时被选择。如果没有可用的合规目标，该能力将会失效。

一些触发式能力是延迟性触发能力，它可以产生延迟性触发，导致该能力在一个稍后的时间点进入效果堆叠，例如在一个回合的结束时。它们也可能使用诸如“在”或“当”这样的词，但未必会以这些词开头。

4. 延迟性触发是作为另一个能力结算的结果而产生的。如果那个本应产生延迟性触发的原始能力被无效或失效，则该延迟性触发将不会被产生。
5. 延迟性触发只发生一次，如同普通的触发式能力一样。如果该触发在下一个可能的机会失败了，它不会再产生另一个延迟性触发来试图再次结算。
6. 延迟性触发能力仍被视为能力，并可能被无效或失效。

当多个触发式能力同时进入效果堆叠时，它们将按回合顺序进行堆叠，由属于回合玩家的能力开始。当轮到每位玩家将其能力置于效果堆叠上时，该玩家将能够选择其自己能力的进入顺序。只有在每个触发式能力都以此方式被置于效果堆叠上之后，回合玩家才会被授予时机，且在时机被依次传递之后，这些触发式能力才有机会结算。

如果在另一个效果或启动正在结算时产生了一个触发，该触发只有在那个效果/启动被完全结算后，才会被置于效果堆叠上。如果一张卡牌在其结算时或结算期间因某个条件而产生了其自身的触发，这被称为[反射式触发](../../yong-yu-ji/you-xi-shu-yu.md#reflexive-trigger)。

触发式能力将具有与其来源相同的类型、属性及其他相关特征。

{% hint style="info" %}
![](<../../.gitbook/assets/image (5) (1).png>)\
例如，来自 Stratagem of Myriad Ice 的触发，也被视为具有水属性和法师法术类型。这些触发将不能指定任何带有法术帷幕的物件为目标。
{% endhint %}
