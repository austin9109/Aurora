---
date: 2024-09-06 22:00:00
layout: post
title: Monthly Update - August 2024
subtitle: First playable profession -- Berserker.
description: First playable profession -- Berserker.
image: /assets/img/aurora/202404/title_04.png
optimized_image: /assets/img/aurora/202404/title_04.png
category: game
tags:
  - game
author: austin
---

Greetings Everyone!  We are meeting again!

I've been absent for a while over the past few months, but development has never stopped! Recently, I've been focusing on the design of the first playable class – the Berserker. This includes the full skill mechanics of the Berserker, as well as the visual effects and icons for the skills. At the same time, I’ve also been working on the combat damage calculation process, making the damage more formulaic while ensuring it can accommodate the game's rich strategic elements. Let’s take a look at what changes have been made!

## New Profession -- Berserker

The Berserker is a powerhouse, a battle-obsessed fanatic who excels at unleashing brute force to ruthlessly attack enemies. The longer the Berserker stays in combat, the more energy—Rage—they accumulate, which can be used to execute various types of skills. Additionally, the Berserker is proficient in using axes and can throw melee weapons as projectiles. When a weapon successfully hits a target, it can also trigger the enchantment effects on the weapon.

Currently, the Berserker has ten skills:

| 名稱     | 類型      | 冷卻 | 消耗 | 說明                                                                                                                                                                                   |
|:-------- |:--------- |:---- |:---- |:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 野蠻咆嘯 | 主動/能量 | 10   | TBD  | 對周圍的敵人發出一陣刺耳的叫聲，有 **33%** 的機率能使半徑 **6** 碼以內的敵人感到恐懼，施加 **恐懼** Buff                                                                               |
| 勢不可擋 | 被動      | 無   | 無   | 狂戰士在進行暈眩 & 睡眠豁免檢定時若失敗，可再多檢定一次                                                                                                                                |
| 怒火中燒 | 被動      | 無   | 無   | 狂戰士在受到傷害後能短暫提升 **4%** 傷害，累積收到的傷害次數越多，增加傷害越高，最多疊加 **5** 層                                                                                      |
| 兇蠻重擊 | 被動      | 無   | 無   | 當狂戰士觸發爆擊時，額外增加 **30** 爆擊傷害                                                                                                                                           |
| 狂爆     | 主動/怒氣 | 30   | TBD  | 狂戰士進入無法阻擋的狀態，在 **8** 回合提升傷害 **20%**，並免疫一切控制，但降低 **10** 閃避與 **20** 防禦。期間內所受到的攻擊不會馬上受到傷害，而是在技能結束後在 **6** 回合內平均承受 |
| 蠻衝直撞 | 主動/能量 | 15   | TBD  | 使狂戰士以直線的方式前進，嘗試衝刺到 **8** 碼距離以內的一個地方，狂戰士將對途徑上任何敵人以及可破壞地圖物件造成傷害。當遇到不可造成傷害的障礙物時(純粹的障礙物)，將中途停止在其前方    |
| 嗜血殺戮 | 主動/怒氣 | 10   | TBD  | 狂戰士消耗怒氣並治療自己，恢復 **15%** 自己的最大生命值。                                                                                                                              |
| 怒氣導魔 | 被動      | 無   | 無   | 狂戰士每擁有 **5** 點怒氣值，攻擊時觸發武器效果的機率提高 **1%**。                                                                                                                     |
| 魯莽揮擊 | 主動/能量 | TBD  | TBD  | 狂戰士以破釜沉舟之勢對目標發起進攻，造成無視所有傷害減免的真實傷害，但同時狂戰士本身也會受到攻擊的反彈傷害。如果狂戰士成功擊殺敵人，則不消耗生命                                       |
| 狂戰之怒 | 被動      |      | 無   | 狂戰士根據他的失去生命獲得攻速及普攻吸血，每損失 10% 生命值獲得 **2%** 攻擊速度及 **1%** 吸血。                                                                                        |
| 戰鬥本能 | 被動      | 無   | 無   | 狂戰士對一名敵人造成傷害後，之後的每次攻擊/投擲物品額外造成 **5%** 傷害，持續時間直到沒有做出攻擊動作或是受到傷害為止。                                                                |


## Full implement of damage caculation



## Remake of Attack process

Players can assign acquired skills to quick slots for easy access during gameplay. To do this, open the skill panel and long-press on the active skill you want to assign. Then, drag the skill icon to the desired quick slot. If the skill can be assigned to a quick slot, you will see a floating skill icon while dragging. Simply release the icon onto the desired quick slot to complete the assignment.

![quickable_ability](../assets/img/aurora/202404/quickable_ability.gif)
*Assigning a skill to a quick slot by dragging.*

## Damage Test -- Training Dummy

---

That's all for this month's development progress. The framework for the skill system has been largely completed. In the upcoming months, I will focus on designing the first playable class in the game. Stay tuned for more updates next month!