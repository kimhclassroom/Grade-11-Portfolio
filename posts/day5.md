# Day 5: 
## Friday, January 16, 2026

Today was the last day for this project so I worked on the final little touches of the project. I had created the end screens depending on which player had scored more points as well as creating the score board on the playable screen since the points were being counted in the background. I had also made it so, to avoid any confusion, have each player's points color their slime/trail color since it would be easier to track and understand who is what and who is winning. I had also helped Jojy out with the power-ups such as helping him with the explosion token. We both had realized that to create the explosion we had in mind (creating a random paint splat that went in different directions) would have been very very difficult to do since it requires lots of complex math that, to be frank, neither me nor Jojy really wanted to do. A way that I found to bypass this and make the explosion still very interesting, was to increase the slime size by a factor of 4 for 1 frame. This had made it so that it looked like a very large blob of paint had appeared as soon as the player touched the explosion token but in reality, it was the hitbox that increased to imitate the very large explosion. After this, I had created a small saveHighScore method which created a txt file and took the percentage of the winning players score and had saved it to that txt file so the next time the player would load back into the game, the file would say that “X player had won with X%!”.

[Daily Logs](dailylogs.md)

[Main Page](../index.md)
