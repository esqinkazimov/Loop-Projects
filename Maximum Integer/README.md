This project examines the process of identifying the maximum value in a collection
of integers. Each of the integers will be randomly selected from the numbers between
1 and 100. The collection of integers may contain duplicate values, and some of the
integers between 1 and 100 may not be present.

Many people would check each integer in sequence and ask themself if the number
that they are currently considering is larger than the largest number that they have seen
previously. If it is, then they forget the previous maximum number and remember
the current number as the new maximum number. This is a reasonable approach,
and will result in the correct answer when the process is performed carefully. If you
were performing this task, how many times would you expect to need to update the
maximum value and remember a new number?

While we can answer the question posed at the end of the previous paragraph using
probability theory, we are going to explore it by simulating the situation. I created a
program that begins by selecting a random integer between 1 and 100. It saves this
integer as the maximum number encountered so far. After the initial integer has been
selected, generats 99 additional random integers between 1 and 100. It checks each
integer as it is generated to see if it is larger than the maximum number encountered
so far. If it is then program updates the maximum number encountered
and counts the fact that you performed an update. It displays each integer after you
generate it. It includes a notation with those integers which represent a new maximum.

After displaying 100 integers, program displays the maximum value 
encountered, along with the number of times the maximum value
was updated during the process.
