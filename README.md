How many lines are drawn each frame? In other words, how often does the for loop run?

The for loops run every 10 pixels. there are total 38 lines, it starts at 10, ends at width(400)-10

What do the first, second, and third appearances of the number 10 do in the code?

The first 10 represents the first line which is the starting point of the loop. The second 10 represents the end line of the loop, which the last line should end at width - 10. The third 10 represents the distance between each line.

How many times does the loop body run each frame, once the x and y arrays are full?

6 times

What are two ways of increasing the spacing between rings?

change "i = i + 10"; change (x.length - i)

How can you make the ellipse trail longer?

  x = x.slice(-110); 
  y = y.slice(-110);
