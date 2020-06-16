---
title: "The Sword Before the Slime"
categories:
  - Dev Log
tags:
  - The Sword and the Slime
---

Since I’ll be wrapping up development soon there won’t be much content for a dedicated devlog. So instead I’ll be doing a series of post mortems reflecting on the development of Sword and the Slime. To kick things of we’ll start at the beginning.

And in the beginning there was no slime in The Sword and the Slime.

At this point I had been to three or so game jams, had a few game concepts that didn’t go anywhere, and had not written a single line of code (I still haven’t). The original idea of this game was more serious in tone and the sword would have been bound to different characters, and if you strayed too far from them the sword would lose its magical power and fall useless to the floor. The intro would have been an “on rails” experience following a world weary, but still powerful, wizard on his last hurrah to stop some calamity or some such. It would be your job to follow him around and protect him as he did his thing and casts this big ol’ mcguffin spell to save the world. But he still dies at the end, very dramatic, very sad, you all would have cried I promise. After all this the sword falls and is left in the dungeon for countless years… only to be found again by a lost and defenseless youth in the dungeon. From that point on the sword would be bound to the kid who would follow the sword, giving the player more direct control of the game. The rest writes itself, protect the kid because you have to not because you want to, fight scary monsters yada yada, guide them through the dungeon, growing bond and trust… would have been great.

But as it turns out creating a dynamic and convincing AI is tough. Who knew.

Like a good and proper game dev I kicked that core design issue down the road. I was sure I’d figure it out eventually.  In the meantime, the “kid” placeholder sprite was a green block. And it was dumb. I mean really dumb. It had the bare minimum amount of functionality. So sure, it would follow the sword around no problem, even if it was off a cliff or into open flame or a maw of pointy bits.

So there I was watching this dumb green block sprint off of cliffs while I contemplated the daunting task of creating a dynamic and responsive character. Watching this pitiful display I thought the green block looked a bit like a generic green slime cube. I giggled at thought and dismissed it. Then I did a double take.

If it was a slime it would be easier to program… it was practically done.

If it was a slime it could eat things

It could grow as it eats

It could shrink as it took damage

It’s size would become a natural health indicator.

It could bounce and jiggle and then some.

The more I thought about it the better it was. Not only did it sound way more fun and original, but more importantly it would cut down on design complexity. The only new problem was tying a flying sword and slime together into a narrative, but that would be much easier to figure out. I’ve learned (the hard way, several times)  that so much of game design is knowing what not to do, and when to cut your losses. Even if it means taking a project in a radically different direction. That being said I’ve still been working on this game on and off for 3 plus years, it is scary to think how far along it would be now if I had stuck to my guns… Looking back I’m glad I made the call I did, and not just for the time and effort saved because The Sword and the Slime is so much better for it, having become this weird silly playful thing.

![sword-in-the-slime-start-menu]({{ site.url }}{{ site.baseurl }}/assets/images/sword-and-the-slime/forest-scene.png)