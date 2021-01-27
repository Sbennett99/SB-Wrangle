# SB-Wrangle for All's Well That Ends Well
## Speaker 1
- Countess

## Speaker 2
- Helena

## Question
Which speaker spoke the most number of times?

## Commands Used

```Bash
#Obtained play text
 curl "http://shakespeare.mit.edu/allswell/full.html" > FullPlay.txt
#Counted the times Countess Spoke and output
 grep ">COUNTESS<" FullPlay.txt -c > TimesCountessSpoke.txt 
#Counted the times Helena Spoke and output
 grep ">HELENA<" FullPlay.txt -c > TimesHelenaSpoke.txt



```
## Conclusion/Answer
Helena spoke more than Countess did