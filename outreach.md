---
layout: page
title: Outreach
subtitle: Teaching programming and bioinformatics
use-site-title: true
---

Engaging young people into computational research can be challenging. Check out these fun, hands-on, and computer free activities for teaching skills in computer science and bioinformatics

* [Code Like a Girl](#code-like-a-girl)
* [Assemble this](#assemble-this)



---------
# Code Like a Girl

<figure>
	<p align='center'>
		<img src="../img/outreach/code_like_a_girl.jpg" alt='Code Like a Girl' height="300px">
		<figcaption><small><i>Demonstrating how you can make your code shorter and more efficient using functions (March 2017).</i></small></figcaption>

	</p>
</figure>

>Learn to think like a computer scientists by writing a program that will get you and your friends around obstacles to make it through a treacherous maze!


While this activity was originally developed for middle school age girls for "Girl's Math and Science Day" @ Michigan State University, hosted by the [MSU Graduate Women in Science](https://gwismidmichigan.weebly.com/), it is suitible for all elementary school age students. For students much younger than middle school, simpler mazes may need to be designed. 


The activity is based loosely off [LightBot](http://lightbot.com/hour-of-code.html), where you have a "robot" (i.e. one of the students) who you are helping through a maze by designing a "program" of step-by-step instructions to make it through the maze. Things get tricky when you introduce functions and limit the number of moves. 

<figure>
	<p align='center'>
		<img src="../img/outreach/maze_set_up.jpg" alt='Maze' height="350px">
		<figcaption><small><i>Puzzle 1 laid out for Girl's Math and Science Day 2018. Old amazon boxes work great, I just had these random crates around my house.</i></small></figcaption>

	</p>
</figure>

Find all of the puzzles and the code cards [here](https://github.com/azodichr/Outreach/tree/master/code_like_a_girl)!

### Step 1. Explain the game with puzzle 1
Explain what the code cards do (i.e. move forward, turn left, turn right, jump, push the box, pick up the candy, etc). Then have the girls write a code to solve puzzle one using as many steps as they want. I like having a strip of tape on the cards and taping them to a black/white board (which is nice cause you can highlight the repeating patterns later).

### Step 2. Writing functions
They probably figure out the game pretty quickly in step one, and if they had unlimited code cards it would be easy for them to solve any puzzle. But here is where you introduce functions. Discuss how computer programs are good for automating repetitive tasks. Then ask them to look for "repetitive" patterns in their code, and move the repetitive part to a function. Then they can run the code by calling their function when that pattern is needed, drastically reducing the number of code cards needed to guide their friend through the maize.

### Step 3. Identifying patterns
Move on to puzzle 2. The goal of puzzle two is to make it from start to finish and pick up 3 candies on the way. There are 3 candies physically close to them and a few more that seem farther away. The trick here is that they don't have enough code cards to get all of the close by candies, but instead have to write a function that allows them to get to the farther away candies. 

### Step 4. Challenge mode
Puzzle 3 is a lot of fun because there are a few solutions, but they all involve writing functions. The patterns in this puzzle are also less easy to spot, so it's best to do this one after they've completed puzzle 2. If you're working in a 30 minute time frame, I would suggest going through steps 1-2 together, then splitting into two groups, group one does puzzle 2 and group two does puzzle 3. Then at the end the groups can do a show-and-tell explaining what they had to do to the other group, talking about why it was difficult, and how they solved it. 

Again, all of the puzzles and code cards are available [here](https://github.com/azodichr/Outreach/tree/master/code_like_a_girl). If you have questions about how to implement this at your own science outreach event please find me on twitter [@cbazodi](https://twitter.com/cbazodi). I would also be happy to add new puzzles to the document so if you design something new let me know!


---------
# Assemble this



<figure>
	<p align='center'>
		<img src="../img/outreach/assemble_this_GMSD.jpg" alt='Puzzle Solvers' height="300px">
		<figcaption><small><i>Middle schoolers hard at work assembling their lego sequence  (March 2018).</i></small></figcaption>

	</p>
</figure>

>Using legos as your DNA, test your skills at assembling your own genes while learning about human and plant genomes and about how scientists use computers to assemble whole genomes!


While this activity was originally developed for middle school age girls for "Girl's Math and Science Day" @ Michigan State University, hosted by the [MSU Graduate Women in Science](https://gwismidmichigan.weebly.com/), it is suitible for all elementary school age students. For students much younger than middle school, simpler puzzles may need to be designed. Similarly, this activity could be enjoyable for high schools if given more challenging puzzles. 


I started the activity with a short presentation generally explaing what a genome is, when the first human genome was sequenced and what that actually meant, and finally and why genome assembly is so challenging. Then we jumped right into assembling our lego contigs! I designed 4 progressively more difficult puzzles. Each one took a pair of middle school age girls between 5-10 minutes to solve. The first two puzzles are straight forward. The main difficulties that the girls had was understanding that just because two kmers had an overlap didn't mean they had to align with each other and generally being willing to move pieces around that they thought they knew the correct location for. 

The next two puzzles were specifically designed to teach the concepts of adequet sequence coverage and repetitive sequence assembly. For puzzle 3, the students were given enouch k-mers to resolve two separate contigs but those contigs could not fit together... after letting them struggle for a while, we stopped and talked about how this actually happens in genome assembly and that one way to solve it is to get more sequencing done to ensure enough coverage. After that, I provided them with three additional k-mers that allowed them to connect their two contigs. For puzzle 4 I did not tell the students how long the final solution was, after all, in a real scenario, you wouldn't know this. However the k-mers that they were given were so repetative that they could assemble it into a very short contig with very uneven coverage. Then, I told them that the sequence was actually supposed to be 17 legos long. A few were able to figure out how to spread out the k-mers to make it the correct lenght, but most struggled. So we stopped and talked about next generation sequencing (i.e. long read sequencing) and how that was helpful for assembling highly repetative regions.

<figure>
	<p align='center'>
		<img src="../img/outreach/assemble_this_example.jpg" alt='Puzzle examples' height="550px">
		<figcaption><small><i>One way to go about solving sequence puzzles 2 and 3... But watch out, sequence 3 has a twist!</i></small></figcaption>

	</p>
</figure>

Find the other puzzles and a break down of how many legos you will need [here](https://github.com/azodichr/Outreach/tree/master/assemble_this)!

