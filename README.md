# Big Data

## Map Reduce

The following exercise can be used to explain the MapReduce algorithm.
It is taken from [this video](https://www.youtube.com/watch?v=bcjSe0xCHbE).

Materials Needed

* Large Deck of Cards (Ideally Multiple Decks, Cambio deck)
* Students to participate
* [Linke to this slide deck](https://docs.google.com/presentation/d/1FrgSc3IqkmhXM3ryz4yQzVG3gjeDgJRmcFUXb27V4M8/edit?usp=sharing) 

## Activity 

The goal of this activity is to demonstrate that when a complex task is done in parallel, as opposed to series it is faster.
The first step in this execise is to explain the task:

> Imagine you are a computer and it is your task to work your way through mountain of data to process:
> In this example, we have a deck of cards, the data, and must count how many cards of each suit there are.
> In this example we are only interested in non-face cards (just numbers).

Next, take a small amount of cards, pass them to one student and ask them to complete the task.
For fun, you could time the student with a stopwatch.
The student needs to come up with the correct answer, but they are told they can only make one pile of cards.

After they complete the task (probably making separate piles) ask the student what was difficult about the task.
They might respond with 

* Number of cards
* Limited by piles

Note here that computation power here is limited and bottlenecked.

Ask the student to do it again, but now they are are allowed to sort their cards into as many piles as they need.
Again, time the student and see how accurate they are. 

Note here that computers are more effecient when they only have to think about one thing (could even relate to vectorization in NumPy).
First step for computers in Map Reduce is to Map, which is just putting similar data in correct areas.
Second, the reduce happens in the counting once data is in the right area.

Now ask, what could make this even faster?
Ideally students will say more people doing the task.

Have four students, instead of one do the task.
Time it.

Lastly, could have more students do more cards, time it, but this is at discresion of instructor.  

End with asking for think, pair, share of comparing MapReduce metaphor to card sorting. 


