# Algorithm-for-Bengali-Error-Dataset-Generation
We present a unique algorithm for Bangla that can be used to generate an error or misspelled Bangla words like we often do while writing in Bangla through the English keyboard. In our work, we made a cluster list and realize the similar pronounced letters in Bangla and replace those letters for making an error word. Our goal is to make the errors in writing as human as possible. We are striving for finding out the mistake patterns of humans while writing Bangla, using an English keyboard with QWERTY layout and use that subject for our work.

1. In file "ErrorWordGenaratorTool.ipynb" we have developed an error word generation tool. By using this code anyone can generate an error word from correct word. Give a Correct word as Input and Output will be a wrong word in the console.

2. In the "Juktakkhor List.txt" file we show 170 constant words of Bengali language, which are mostly use.

3."Juktakkhor-handling-rules.pdf" - In this file we proposed 20 rules for handling constant word.

4." Phonetic Similar Cluster Replacement.txt" - here we proposed a Dictionary for which character is phonetically similar.

5." Single Letter Mispressed Cluster Replacement.txt" - here we proposed a Dictionary for which character is adjacent to the QWERTY keyboard layout.

6."Single letter Mispressed cluster insertion.txt" - here we proposed a Dictionary for which character is As well as mixes with the adjacent character in the QWERTY keyboard layout.
