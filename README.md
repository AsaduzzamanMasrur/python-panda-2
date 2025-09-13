# python-panda-2

Pandas Exercise 2

Create a 10 by 10 matrix and name the columns A to J (use integer random values from 0 to 20)

Visualise the first three rows and last three rows

Create a function that returns square of a given number and apply it to column A of your DataFrame

Well, this seemed to have been temporary, can you do it permanently?

Now recall your data frame columns and rows

What’s the size of your DataFrame?

Sort the values in your matrix by using column J in ascending order

Is it permanent? Check it, and then find a way to make it permanent

Let’s say you just made a mistake and you want to go back to the original order in your dataframe… how can you do it? (remember the order of the index values)

Oops, when you used inplace=True, it’s done for good. You can reset the index values to be in order, but the J column won’t revert back to what it was

Ooohh, we seem to have a new column… let’s check it

How can we convert one of the columns into index?

So do you see how confusion and distortion in the main data can occur if you are not careful? At the moment our Index column is distorted.
Let’s start again…

We will create a column called Index, and fill it up accordingly, then we will set it as index.
Try doing it, and then look below.

Conditional Manipulation of the DataFrame and Adding New Columns

Add new columns that will indicate high values in Column A and B. We want to see where values are above 15.

OR

Add a new column which indicates if the sum of the rows is Above 90.
We will use a for loop.
