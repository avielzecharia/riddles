This page contains a collection of exciting (it's all relative 🤓) riddles of different levels from various fields (Math & CS). 
The specific field/level of each riddle does not mentioned on purpose - **That's why it's fun**.

## Tips & Tricks 💡
- Try to reduce the riddle to the primitive case, then exapnd your solution
  - e.g. given a large parameter, starts with the minimal possible one instead of the original
  - Solve it like a dumbass, trying to find the rules
- Reframe the problem with a workable mathematical model
  - e.g. functiosn, points, graphs, etc.
- Start with the trivial algorithm, then understand why is it so wastful
- You are lost
  - Understand why all existing tricks does not work here, what have been changed?
  - Search for related topics on internet
  - Sleep & Shower & Drive with this riddle in your head
  - DO NOT GIVE UP !
- After solving the riddle (👌), try to exapnd your solution to the general case
  - e.g. changing parameters, cancel existing assumptions, ask more interesting questions
- Each riddle teaches you a certain method of action that is repeated in many other places
  - understand the big picture, and think how this trick can be reused
  - e.g. XOR operation

Ping me for riddles\solution proposal, clues, or anything else on `avielz1199@gmail.com`.

Enjoy 🎉

* * *



# "Let there be light", God. 🔦
In Israel, two cities are called "friends" if they have a common underground electricity infrastructure.
Each city has a button, which flips the lighting state in the city - due to infrastructure issues, this also changes "friends" state.
During the day, all lights are turned off in Israel.

- Night is coming, is it possible to turn on the light in Israel?
- If you do, describe how can you do that (efficiently?)
- If you do, how many possible ways there are to light Israel up?


# Are you in? 🫱🏾‍🫲🏾
You are given a polygon in Euclidean space, and a location which describes you.

- How can you tell if you are inside or outside the polygon?


# Round Table 🪙
Alice and Bob playing a game. In each turn the player must put a 1₪ coin on a round table. 
The first who has no left space to put the coin - loses.

- Alice may choose to whether start or not (ladies first), can she always win?
- If she do, describe Alice strategy


# MinDiv 🔢
We define the MinDiv of number n to be the minimal number which is divided by all number from 1 to n.

- Give a formula for DivMin(n)
- How can you calculate MinDiv efficiently?


# Gen-Y 👩🏽‍👦🏾
You are given two linked lists in ROM.

- How can you determine if they merged?
- Describe a way to find the merge point


# Nightmare 🌃
Calculate the exact value of the following expression:

$$\int_{0}^{\pi/2} ln(4-sin^2(x)) dx$$


# Drunk Fly 🪰
Two subway trains of distance $S$ are moving toward each other at constant speed. 
A poor fly got stuck between them and flew back and forth at constant speed.

- What is the distance the fly will travel until it crashes?


# 50-50 🌓
Let S be a group of numbers of size 2n+1.
It is given that every subset of size 2n can be divided into two groups of equal size and sum.

- Prove that all S members are equal


# Building Pyramids 📐
You are given a set of balls divided into random number of piles.
At each step, a ball is taken from each pile and a new pile of balls is created from them (empty piles are ignored).

$$\#balls = T_n = \frac{n(n+1)}{2}$$
```
OOO, OOO  ->  OO, OO, OO  ->  OOO, O, O, O  ->  OOOO, OO  ->  OOO, OO, O  ->  OOO, OO, O  ->  ... [Pyramid] ...
```

- Prove that after finite number of steps we will reach the "Pyramid" stable state.


# Binary Gold 🥇
Alice and Bob play a game for 100 gold coins.
In each turn, every player must take a number of coins that is a power of 2.
The last one to take coins - wins.

- Alice may choose to whether start or not (ladies first), can she always win?
- If she do, describe Alice strategy


# Low Cost Flight ✈️
100 passengers board a plane with 100 seats where each passenger has a ticket with their seat number. 
Unfortunately, the first passenger lost his ticket and he sat in a random seat. 
From now on every passenger who enters will sit in his seat if it is free, otherwise he will sit in a completely random seat.

- What is the probability that the last passenger wull take his seat?


# Sahara Desert 🏜️
Two friends are lost in the Sahara desert with a single water bottle and a marker.

- How can they divide the water equally


# A Little bit Communication 📳
Alice and Bob each get a number - where one is the square of the other.

- What is the minimal number of bits that must be transferred, in order for them to decide who received the square number?


# Hamilton Kindergarten 🏡
All the children are standing in a circle in the kindergarten yard waiting to play.
Teacher: "Pass the ball between you, but a child must not receive the ball twice."
The children: "It's too easy!"
Teacher: "Okay, each pair of children can only be given in the direction that I will choose in advance."
The children: "Hmmmm"

- Will the children always be able to succeed in this game?


# Rise From the Ashes #️⃣
$$HASH(x) = SHA256(x) \mod n$$

- Find a collision with constant memory and linear time complexity


# Cover Me ! 🪖
Google has a server farm where each server targets a different market.
Therefore, it is less likely that two servers will be hacked on the same day. 
Assuming that a server has been hacked, we would like to restore it to the state of the beginning of the day.

- How can you ensure such a backup for the server farm given a single backup server (efficiently)?


# Snail 🐌
You are given a pointer to the head of a linked-list stored in ROM.
A snail-list is a linked-list which contains a circle.

- Determine whether the list is a snail-list with linear time complexity.
- Find the origin of the circle.
  - Analyze your time complexity as a function of tail and circle length.


# THE MATRIX 0️⃣
01-Matrix is a matrix of size nXn which contains zeros and ones. 
The only permitted operation on a given matrix is flipping bit state of an entire row|column|diagonal.

- Starting from a 0-Matrix, can you get to 0-Matrix with 1 at the top right cell?


# Chaos in the Library 📚
The library has n books on a shelf capable of containing exactly n books.
Each book contains a unique number from 1 to n on its cover.
The books are messy and the librarian wants to sort them, but there is no extra shelf.
Therefore, the librarian randomly selects a book that is not in its place, and places it in the appropriate place.

- Prove that the books will be ordered after finite number of steps.


# Train to Nowhere 🚋
The ticket-seller is inside a circular connected set of train cars.
In every train car there is a lamp that may be turned on/off. Note that the initial state of the lamp is unknown.

- How can the ticket-seller calculate the length of train (efficienly)?


# Broken Board ⬜💥
You are given a board of size 2nX2n, and a infinite number of rectangles of size 1X2.
Unfortunately, the board fell and its lower left and upper right cells were broken.

- Can the broken board be tiled?


# Cheers 🍷
The king has 1000 wine bottles, but some of them are poisoned.
It is known that the poison takes effect after exactly 24 hours and kills the person who drank even a sip.
The king wants to find the poisoned bottles, and is ready to sacrifice as few of his servants as possible.

- There is 1 poisoned bottle, and 24 hours - find the poisoned bottle!
- There is 1 poisoned bottle, and 48 hours - find the poisoned bottle!
- There are 2 poisoned bottles, and 24 hours - find the poisoned bottles!


# CS 1.6 🔫
101 professional gamers are playing together on the awp_india map.
Each pair of players able to shoot each other, and are at a different distance from any other pair of players.
At the same time, every player shoots the nearest player to him.

- Will everyone die?


# Exploit 🔑
You are given a vulnerability which allows you the following primitives:
1. Writing 65536 consecutive bytes to 0xFFFFFFBFFC000000.
2. Reading 2 bytes from 0xFFFFFFBFFC000000 plus a secret key which is small than 65536.

Each primitive can be used exactly once.

- Use these two primitives in order to find the secret key.
