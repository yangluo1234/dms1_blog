---
title: Homework Tasks_Week8, Session1
published_at: 2024-09-17
snippet: Homework Tasks_Week8, Session1
disable_html_sanitization: true
allow_math: true
---
#  2024 Sem2 DMS1: 13:30 - 16:30 class

## Project Process ## 
 **Lake**
![week8](lake.jpg)
![week8](post-process.jpg)

<p>This week, I readjusted the proportions of the indoor living space and outdoor terrain. For the indoor space, it should feel tight while outdoors, it should be more open. These contrasts enhance the narrative journey of my environment.</p>

<p>Additionally, I added a lake to the outdoor terrain. I used some free assets from the Unity Asset Store to construct the lake, which adds depth and realism to the natural environment. I also implemented post-processing effects to blend the player's camera when they go underwater. This was a key feature to ensure that the underwater experience feels immersive, with a smooth transition between above and below water.</p>

**First Person Player Controller**
![week8](player_jump.jpg)
![week](open_door.jpg)

<p>Some issues I found during my development, one is the original first-person controller didn't include jump functionality, which made navigating the stairs in the house so difficult. To fix this, I followed a tutorial on YouTube and successfully added a jump script to the player controller. Now, by pressing Space, the player can jump and move upstairs. This small adjustment ensures that the player can fully explore the house and interact with all areas.</p>

<p>Another one was getting the door functionality to work properly. While browsing through assets, I noticed that many doors could be pushed open by the player. However, in my case, the player was unable to interact with the door. I spent a lot of time trying to solve this issue. Finally, I realised that I needed to add a script to the player controller. This script would allow the player to interact with the door's rigidbody, so the door could be pushed open. After making this change, the door worked as expected. This was a good learning experience and improved my Unity skills. </p>

