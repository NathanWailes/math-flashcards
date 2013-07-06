You can find the videos here:
http://www.artofproblemsolving.com/Videos/index.php?type=minis


2009 State Sprint #14 - If you roll 3 fair 6-sided dice and add up the numbers, what's the probability that you'll have "9"?||You need to add up all the different ways to get a 9, and then divide that by all the different possible rolls you can get.  He made three columns: first he made a column showing what the highest die could be while still getting 9, then he made a second column that showed the number of ways to get 9 with each of those highest die rolls, and finally he made a third column that showed the # of ways to get each of the results in the second column.  He ended up with 25 different ways to roll a 9.  He then divided by the number of possible different rolls, which is 6x6x6, or 216.||



2009 State Sprint #15 - If you have three people in a race, how many different ways could the race end, given that ties are allowed?||You can't use a simple formula, like 3!.  So you need to track the different types of cases: You could have a) 1 person finish first, or b) 2 people first, or c) 3 people finish first. For the first case, there are three ways to have the first-place person, and then three ways the 2nd/3rd place people could end up: you could have a tie, or one guy in front of the other (2 ways to do that).  For case b), where two people tie for first, there are 3 ways to pick who DOESN'T finish first.


A second way to solve this question is to track what happens based on the number of ties: a first case is where 0 people tie, a second case is where 2 people tie, and a third case where all three people tie.
Derive the formula for an arithmetic sequence.||Richard Rusczyk does it with those hanging monkeys from that board game I can't remember the name of. You start at one monkey (called "a"), then put the next monkey a certain distance ("d") away, then put the third monkey the same distance from the second monkey, etc. So the nth term will be a + (n-1)d.


MATHCOUNTS Mini November 2009 - You have one arithmetic sequence that goes "30, 40, ..." and another arithmetic sequence that goes "30, 20, 10, ...". What is the difference between the 51st term of A and the 51st term of B?||Instead of using the formula for an arithmetic sequence, just thinking about the pattern of the situation. Rusczyk does it with monkeys. After one step, the monkeys will be 20 apart. After two steps they'll be 40 apart. We're wondering what will happen after 50 steps in each direction. 50 steps times two directions is 100 total steps, and 100 times a step length of "10" is 1000.



MATHCOUNTS Mini November 2009 - You have two arithmetic sequences. One goes "2, 5, 8, 11", the other goes by "3, 10, 17, 24". Question: What's the largest number less than 500 that shows up in both sequences?||Rusczyk starts by looking for the first number that shows up in both sequences; it's 17 (he continues the 2/5/8 sequence). He then creates a number-line out of his toy barrel-of-monkeys and thinks about how often the two sequences will come into alignment; it turns out it'll be every 21. So he asks, "Ok, how can we quickly get close to 500?" and he just multiplies 21 by 10 to get 210, and then by 20 to get 420, adds it to 17 to get 437. Then he starts incrementing by 21: 437 + 21 = 458, 458 + 21 = 479, and 479 + 21 = 500, but we're looking for a number less than 500 so the answer is 479.



MATHCOUNTS Mini December 2009 - If x + 1/y = 1 and y + 1/z = 1, what is xyz?||Richard first tries to get an xyz in the given equations by multiplying the first equation by yz and the second equation by xz. That doesn't lead him very far, so he then just tries putting 2 in for x, and solves for y using the first equation, then solves for z using the second equation, and then uses the values of x, y, and z to get xyz. He then goes back to his "smart" approach and just computes xyz by substituting variables, and everything cancels to get -1.|| What should you do if you're confronted with a problem that you don't know how to tackle?||Step 1) Don't Panic!Step 2) Do something!||



MATHCOUNTS Mini January 2010 - Each of the integers 1 through 16 is written on a separate slip of paper and these slips are placed in a pile. Jill will randomly draw slips from the pile without replacement and will continue drawing until two of the numbers she has drawn from the pile have a product that is a perfect square. What is the maximum number of slips that Jill can draw without obtaining a product that is a perfect square?||Richard starts with a simple case (1 through 2) and just keeps adding one number at a time. He eventually groups numbers by whether they can't be selected together (like listing people who hate each other when figuring out who to invite to a party), and he figures out that you can't select 2 perfect squares, or two numbers that are double a perfect square, or two numbers that are 3 times a perfect square, etc. He then uses the pigeon-hole principle to prove that the max you'll be able to select is 11.||