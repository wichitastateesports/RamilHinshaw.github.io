---
layout: default
title: Oot Multiplayer test With PUN
tags: unity3d c# ludumdare
category: project game
imgDir: /img/projects/ootOnline/
description: Very old project I worked on when Unity was still very new. It is no secret of love the Legend of Zelda franchise and I had this set goal recreating my favorite game from my childhood and getting multiplayer working so my friends and I could play. It was a very weird and frustatrating expereince trying to train my brain on what information the master and clients were suppose to have, but it was a valuable experience.

---


Multiplayer Network Test (PUN) with Legend of Zelda
================

![Picture](/img/projects/ootOnline/1.png)
Favorite child game that was recreated with multiplayer. This was a simple three day project  to understand how to implement multiplayer into my games in the future. I used the popular Photon Networking SDK (https://www.photonengine.com/en-US/PUN) and this was before Unity had its own comparable MP service (which I still think shadows in comparison to PUN)

![Picture](/img/projects/ootOnline/2.png)
The main feature of the game besides the iconic franchise was adding the ability to chat with other fellow players. Of course seeing them move and updating their position is the main point of multiplayer, but communication/interaction is so important for this type of game.

![Picture](/img/projects/ootOnline/3.png)
Once I understood the whole networking API from Photon, I've added more adjust like having the names display on top of the characters. The hardest part of the whole multiplayer course was understanding the master client relationship. I had to take into account what happens if the host disappears or more characters are added. How does information sync up efficiently and as fast as possibly between all the clients. And most important, what information should the client have vs the master. Really was a nice experience that gave me a whole new view on multiplayer services and I really appreciate those network developers a lot more now.
