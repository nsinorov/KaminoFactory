## KaminoFactory

The clone factory in Kamino got another order to clone troops. But this time you are tasked to find **the best DNA** sequence to use in the production. 

You will receive the **DNA length** and until you receive the command **"Clone them!"**, you will be receiving a **DNA sequence of ones and zeroes, split by '!' (one or several).**

You should select the sequence with the **longest subsequence of ones.** If there are several sequences with the **same length of the subsequence of ones**, print the one with the **leftmost starting index**, if there are several sequences with the same **length and starting index**, select the sequence with the **greater sum** of its elements.

## Input / Constraints:

	The first line holds the length of the sequences – integer in the range [1…100].
	On the next lines, until you receive "Clone them!", you will be receiving sequences (at least one) of ones and zeroes, split by '!' (one or several).

## Output:

    The output should be printed on the console and consists of two lines in the following format:
    "Best DNA sample {bestSequenceIndex} with sum: {bestSequenceSum}."
    "{DNA sequence, joined by space}"

## Examples: 

![Capture](https://user-images.githubusercontent.com/45227327/194097005-38816ad5-b2a8-46fb-b067-caebc2882629.PNG)
