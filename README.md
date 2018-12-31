# AdamAI
<p align="center">
An A.I. that learns to traverse a maze using the genetic algorithm.

Using the genetic algorithm, the A.I. “learns” to go through the maze using the concepts of natural selection and survival of the fittest. The base of the natural selection is firstly a single generation of A.I.s (all randomly selected) and as they go through the maze, the fittest is selected by examining the shortest distance to checkpoint in least amount of moves. By increasing the number of moves available to them every five generations so that they master the moves more efficiently (incremental learning), they are able to ‘remember’ old directions and pass on genes of efficiency to later generations.

**Note**: It takes about ~50 generations for the A.I. to reach the first checkpoint (when the evolution speed is set to 6), ~120 generations for the A.I. to reach the second, and so forth. The learning takes time but it eventually does win, never missing a checkpoint or dying in the face of enemies. Your own evolution took about 8 million years, so have patience with Adam A.I.
<p align="center">
<img src="https://i.imgur.com/zpuw4bf.png"/>
 </p>
</p>

## Features
* **The A.I**: The little square at the start black end is the 'fittest' from the entire generation. To see the generation itself, press SPACE on your keyboard to do so. 
* **Evolution Cycle Controls**: You are able to change the population size (more/less chance for a better fit), mutation rate (how much the A.I. deviates from the norm), and evolution speed (just make the process faster; set to 6 if you do not want to wait forever). You are also able to increase a certain number of moves by a certain number of generations (the recommended amount is 5 moves per 5 generations).
* **Play it Yourself**: Press P to play the game yourself. For a human equipped with a mind adapted from years of evolution, this should be easy to you. But once the A.I. beats the game, you'll find that you're more prone to mistakes than it is. 
* **Evolution Highlights**: Press G to replay evolution highlights.

This project was jointly created with a very nice human, [@RaiyanRahman](https://github.com/RaiyanRahman).

Check out [Code Bullet](https://github.com/Code-Bullet) for a rudimentary basis of the genetic algorithm.
