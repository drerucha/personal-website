---
layout: post
title: "My Answers to Some Brain Teasers"
tags: [animation]
---

Here are my answers to the brain teasers I was asked during [my second DreamWorks interview.][second-dreamworks-interview] What I’ve written here is definitely more succinct and cogent than what came out of my mouth during my interview, but for fun, let’s pretend that whatever came out of my mouth during my interview was precisely correct.

## All That Sand and Nothing to Count It With

**Question.** How would you count all the grains of sand on a California beach without the use of sophisticated tools?

**Answer.** Assume you have an unsophisticated ruler. Line up grains of sand until your line measures one centimeter long. Assume it takes ten grains. Ten is arbitrary. Ten might be wildly incorrect, but it’s an easy number to work with, and it’s reasonable enough.

If your interviewer won’t let you have an imaginary ruler, then tell him/her that you used your hand as a ruler. One half the length of your top pinky finger joint is a decent estimate for one centimeter. Exact? Unlikely. Close? Probably. Does it matter? Not really.

This tiny piece of information (10 grains = 1 centimeter) opens the floodgates to many larger pieces of information. For instance, knowing how many grains it takes to measure out a 1 centimeter line is all you need to compute the number of grains it takes to fill 1 cubic centimeter: side length * side length * side length = cube volume, so 10 grains along a side * 10 grains along a side * 10 grains along a side = 1,000 grains in a cubic centimeter.

Using the number of grains it takes to fill 1 cubic centimeter, you can compute the number of grains it takes to fill 1 cubic meter, which is a scale more appropriate than cubic centimeters when working with something as large as a beach. There are 100 centimeters in a meter, so there are 100 * 100 * 100 = 1,000,000 cubic centimeters in a cubic meter. We’ve already estimated there are 1,000 grains of sand in 1 cubic centimeter, so there must be 1,000 * 1,000,000 = 1,000,000,000 grains of sand in a cubic meter.

Next, you need to estimate the number of cubic meters in your beach. There are a bunch of approaches you could take to do this. If the beach is small enough, you could pace it out to get a surface area estimate. If the beach is too large to walk, you could try estimating it’s surface area in terms of football fields. How many football fields long and wide does it look? If the beach is too big for that, you could ask for a map, and work out an estimate that way.

It really doesn’t matter. There are no right answers with estimation questions. These questions are all about making reasonable assumptions and working with what you assume.

Let’s assume it’s a small beach, and we pace it out. 100 meters long. 50 meters wide. Again, these numbers are arbitrary. Think out loud. Tell your interviewers what numbers you’re using and what assumptions you’re making. If they disagree, they’ll tell you, and then you can revise.

Next, we need to know how deep the beach is. To answer that, we need to make an assumption about when a beach is no longer a beach. Let’s assume a beach stops being a beach when it runs out of sand. So, once we dig deep enough that the sand becomes dirt or clay or something, then we’re no longer dealing with a beach. Let’s say the sand stops at 10 meters deep. Why? Because. Arbitrary, remember?

So, our beach has the following dimensions: 100 meters long * 50 meters wide * 10 meters deep = 50,000 cubic meters. We know there are 1,000,000,000 grains of sand in one cubic meter because we estimated that earlier. So, we know there are 50,000 * 1,000,000,000 = 50,000,000,000,000 grains of sand on the entire beach!

Whew. That wasn’t so hard, right?

## The Night Is Darkest When I’m Folding My Socks

**Question.** You have a drawer with 12 white socks and 12 red socks. The power is out in your room. How many socks would you have to pull out of your drawer to guarantee a match is made? How many socks would you have to pull out to guarantee two matches? What is the formula for matching any number of pairs of socks?

**Answer.** One match: A minimum of three socks must be pulled out. In the worst case, the first two socks pulled out will not match (one red, one white). In this case (the worst case), the next sock pulled (sock number three), no matter the color, will match one of the two socks already picked.

Two matches: A minimum of five socks must be pulled out. We start with the case where we made one match by pulling out three socks (say two red socks and one white sock). In the worst case, the fourth sock pulled out does not make a second pair (a red sock in this case). Now we have one complete pair (two red socks), and two socks of different colors. Now, similar to the previous case trying to make one match, the fifth sock that is pulled out, no matter the color, will create the second match.

Three matches: A minimum of seven socks must be pulled out. We start from the last case (three red, two white). We can think of this as two pairs + one red sock. We care about the worst case, so we pull out a white sock. This makes six socks. The seventh sock is guaranteed to make the third match.

Any number of matches: For n pairs, (n * 2) + 1 socks must be picked to ensure n matches are made.

## Get These Blue Balls Out of Here!

**Question.** There are three boxes. One with all red balls. One with all blue balls. One with red and blue balls mixed. All three boxes are mislabeled. Can you properly label all the boxes after only drawing a single ball? How?

**Answer.** Yes, it is possible.

Since we are told all three boxes are mislabeled, pulling a ball from the boxes labeled “Red” or “Blue” may not provide usable information. For instance, if we draw a red ball from the box labeled “Blue”, then that box could have either only red balls or a mix of red and blue balls. It’s impossible to know. The same is true if we draw a blue ball from the box labeled “Red”.

Therefore, we must draw a ball from the box labeled “Mixed”.

If we draw a red ball from the box labeled “Mixed”, then we know that box must contain only red balls. We know this because we know the box is mislabeled, and therefore, we know the box cannot contain both red and blue balls. And, since we just pulled a red ball out of it, we know it’s not the box of blue balls. So, now we know the box labeled “Mixed” is actually the box of red balls, which leaves the boxes labeled “Red” and “Blue” to figure out. One contains only blue balls, and the other contains the mixed balls.

Remember, all the boxes are mislabeled, so the box labeled “Blue” cannot actually contain only blue balls. Therefore, we know the box labeled “Blue” must contain the mixed balls. This leaves the box labeled “Red” the blue balls.

If you had drawn a blue ball from the box labeled “Mixed” in the beginning, you would be able to properly label all three boxes using similar logic.

## Light as a Feather, Stiff as a Counterfeit Coin

**Question.** You have eight coins. One coin is counterfeit and is heavier than the other seven, which all weigh the same. You have a balance scale. How can you identify the counterfeit coin using the scale only twice?

**Answer.** Separate the coins into three groups–three, three, two. Place the two groups of three on the scale (one group of three on each side).

Case I: If the two groups of three coins weigh the same, then the counterfeit coin must be in the group of two. Place the two coins from the group of two on the scale (one coin on each side). The heavier coin is the counterfeit coin.

Case II: One of the two groups of three is heavier than the other group of three. Combine the lighter group of three coins and the two coins not weighed to form a group of five coins you know are not counterfeit. From the three coins that might be counterfeit, place two on the scale (one on each side). If one coin on the scale is heavier, then the heavier coin is the counterfeit coin. If the two coins on the scale weigh the same amount, then the coin not on the scale must be the counterfeit coin.

**Bonus teaser.** This weighing problem is a much simpler version of another brain teaser I like.

*An evil king sends an assassin to take care of the evil queen who tried to poison him. Of course, her trusty guards catch the assassin before any harm is done. The queen notices that the assassin is quite handsome and doesn’t really want to punish him by death. She decides to test his wisdom.*

*The queen gives the assassin 12 pills which are all completely identical in shape, smell, texture, and size, except 1 pill has a different weight. The queen gives the man a balance and tells him that all the pills are deadly poison except for the pill of a different weight. The assassin can make 3 weighings and then must swallow the pill of his choice. If he lives, he will be sent back to the bad king’s kingdom. If he dies, well, that’s what you get for being an assassin.*

*Only one pill is not poison and it’s the pill which has a different weight. The assassin does not know if it weighs more or less than the other pills. How can he save his skin?*

Shoot me an email if you want the solution to this one, and you can’t find it through Uncle Google. It’s a head scratcher.

## Fibonacci and Prime Walk Into a Bar…

**Question.** Given the Fibonacci number sequence and the sequence of prime numbers, which one grows faster?

**Answer.** First, compare the first Fibonacci number against the first prime number: 1 (Fib) vs. 2 (Prime). Then, compare the second Fibonacci number against the second prime number: 1 (Fib) vs. 3 (Prime). Then, the third: 2 (Fib) vs. 5 (Prime). Keep going. When you get to the eighth set, you’ll see the sequence of Fibonacci numbers overtake the sequence of prime numbers. Test a few more to ensure this trend continues, and you’ll have your answer.

You’ll be tempted to solve this problem algorithmically, but that’s not necessary. Offhand, I don’t even know what an algorithmic solution would look like. Work simple. Simple answers are often enough. Simple answers are often preferred.

## In Conclusion

A lot of brain teasers have “gotchas” built in. Meaning, the solution is obscured by some trick or unintuitive interpretation, but once the trick is known, the solution becomes obvious. With those kinds of questions, the right answer vs. a wrong one is usually determined by whether or not the person answering has heard the question before. I don’t think those are good interview questions.

These questions aren’t those questions. None of these have gotchas. While still not great interview material, in my opinion, they are fair.

These questions are also constrained enough that you can feasibly brute force the solution (work through every possible case you can think of until you reach the solution). For instance, pretend you separated your eight coins from the scale problem into two groups of four at the start instead of three groups of three, three, and two. Your next step would be to place all eight coins on the scale, four on each side. One side would be heavier, and you’d know the counterfeit coin was among the heavier group of four. Now, you’re left with four coins and only one more use of the scale. How do you locate one coin within four weighing only once? You can’t. Back up. Try a different approach. Your next attempt would probably be the correct three-three-two split.

In an interview situation, making mistakes is allowed as long as you make them out loud. Your interviewers want to hear you gather and parse information. They don’t learn anything about you if you’re silent, even if you do produce correct answers. Plus, if you get stuck on a problem while thinking out loud, your interviewers will know exactly where you’re stuck. They can then help you get unstuck.

Cheers.

[second-dreamworks-interview]: {% post_url 2015-04-19-my-second-interview-with-dreamworks-animation %}
