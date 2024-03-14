---
date: 2024-02-09 12:00:00
layout: post
title: Introduction to Aurora
subtitle: A beautiful game world that you might interested in.
description: A beautiful game world that you might interested in.
image: ../assets/img/aurora/introduction/helloworld.gif
optimized_image: 
category: game
tags:
  - game
author: austin
---

## Overview

Aurora is a turn-based game crafted based on classic Roguelike mechanics and elements but also integrated some style of open world in mind. The storyline revolves around the character encountering a life-threatening event in their original world. On the brink of consciousness, they are transported to a distant realm known as 'Aurora.' Players must find a way to return to their original world before their soul completely dissipates, or they will be forever trapped within there.

The game is primarily developed using the Unity engine and designed with C#. As a widely-used game development framework, there are many tutorial documents and videos available online, providing substantial assistance to beginners like me in game development.

Following are the core concepts I focus on while designing this game:

- Procedurally generated dungeon & world content.
- Rich and deep character development strategy.
- An appropriate game duration that encourages players to experience the fun of the game as much as possible in each round.
- Not just constantly engaging in battles with enemies, but also having interesting interaction with the game world.

(This area is still somewhat vague for me, I'm presenting it in a more general way for now.)

After a period of effort, the character can finally explore the game smoothly.

![game_snip](../assets/img/aurora/introduction/general_level.gif)

## 2023 Retrospective

In early 2023, I spent a amount of time understanding basic knowledge of Unity and its engine framework. This included transitioning from Object-Oriented Design concepts to Component-Based Design, and other mechanism which would influence efficiency of the game during runtime. After that, I start to research on how to build a framework for turn-based games, aiming for high flexibility and scalability in game content. 

Simultaneously, I delved into understanding the elements of Roguelike games and how to seamlessly integrate them into the framework that I designed. Achieving the integration of these elements in a short period is not an overnight accomplishment, but every successful endeavor is the result of continuous steps, no matter how small, eventually leading to the finish line.

Throughout the entire year of 2023, I successfully achieved the following goals:

- Developed a fully customized and controllable game content serialization system, capable of seamlessly saving game progress and restoring it entirely upon the next game launch.
- Designed a turn-based game engine framework, encompassing synchronization of animations between players and other characters, and minimizing latency for an optimal player gaming experience.
- Established a game world content builder framework, featuring procedurally generated levels, level content and styles based on predefined logic, and the ability to freely switch predefined level content and builder options within the editor.
- Strived to write highly flexible code to ensure easy expansion of game content and the efficient reuse of previously designed game components.

![battle_scene](../assets/img/aurora/introduction/battle_example.gif)
*A demonstration scene of a battle with monsters*

However, during this process, I encountered some challenges:

- The majority of the game assets I currently use are created by the talented u/RafaPixel. He is truly a gifted creator. Due to my pursuit of a specific game art style, I initially spent a lot of time browsing material websites like itch.io. However, obtaining game assets with a similar style and an affordable price proved to be quite challenging, causing significant frustration due to the difficulty in acquiring suitable game assets.
- In the Aurora game world, the coverage area of many characters is not simply a 1 x 1 size. Therefore, additional effort is required to handle these annoying issues in pathfinding and FOV algorithms.

![large_grid_object](../assets/img/aurora/introduction/large_area_grid_object.gif)
*A character who occupies more than one grid can make things become complicated.*

- While I ultimately achieved a customized serialization system, the process was extremely lengthy and tedious. For any game developer, designing engaging game content and mechanics is much more enjoyable than creating a reliable code structure. Moreover, investing a significant amount of effort is necessary to feel the gameplay brought by the system. This type of task often leads to frustration and setbacks.

## 2024 Outlook

While reviewing the accomplishments mentioned above, I feel satisfied and proud of what I've achieved so far. However, at the same time I know that there is still a long way to go before reaching the final state I want to be there.

After a period of thought, I have decided to set the following goals for this project in 2024:

* Before delving into the "open-world content" of the game, there will be a smaller-scale area serving as a transitional stage that connects the main storyline and the core gameplay elements. In this chapter, I anticipate having approximately 3 to 4 explorable areas and a significant segment of the main game plot. I hope to seamlessly fill this portion of the game content.
* During the search for inspiration, I often admire the pages and communities established by other creators, gaining valuable insights from both of them. Simultaneously, I want to record my creative process and ideas, thoroughly "enjoying the game development journey". Therefore, I plan to establish a webpage related to the game and other community platform accounts like Twitter to share these information.
* Currently, most of the game's assets come from paid material websites. However, the content styles provided by these sites vary greatly and may not all align with the game content I want. After some struggles, I realized that creating the ideal work requires the ability to create original materials, whether as an individual or a team. So I've decided to enhance my skills in artistic drawing to create basic assets and simultaneous outsourcing parts of works to other creators.(If anyone reading this is interested in becoming part of this project, feel free to message me anytime!)

In Roguelike games, diverse item effects and complex yet deep character development strategies have always been the essence. At the same time, the unpredictable game content with each new playthrough will immerse players in the challenge repeatedly. In 2024, I will continue to refine the foundational systems of the game, improving the design and functionality between each subsystem.

In summary, most of 2023 was spent on building and refining foundational systems. Therefore, I hope to make 2024 a significant leap forward in filling the game with playable content, truly beginning the "first step in designing a game."

Thanks for everyone who read this article. Looking forward to our next meet!