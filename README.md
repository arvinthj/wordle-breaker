# Wordle Breaker

A minimal wordle breaker written in Vanilla JS that aims to break the day's wordle within the allowed number of guesses. If you are unaware of what wordle is, do check out https://www.powerlanguage.co.uk/wordle/. It's a simple guessing game that has turned into a worldwide phenomenon by now (Circa. January, 2022)

Well, now I know that there is no fun in letting a system solve the day's wordle rather than solving it yourself. I do think the same way myself. But this was still a fun experiment to carry out over the weekend. So this is just me wanting to share the results across.

![alt text](https://github.com/arvinthj/wordle-breaker/blob/master/wordle-breaker.gif?raw=true) 

If you are curious to know how it goes on about guessing the word, feel free to take it for a spin.

## The Process

To arrive at the predictions, the wordle breaker follows a process of elimination and selection that works based on the following two factors:

1. How frequent is a letter present in the given sample of all 5 letter words?
2. How likely it is for a letter to be present at a particular position in the given sample of all 5 letter words?

## Take it for a spin

To see the wordle breaker in action, please do the following:

1. Open wordle in the browser of your choice: https://www.powerlanguage.co.uk/wordle/
2. Open up the browser's developer console. The steps to be followed to open this up varies from browser to browser. How about you check this out for further context? https://balsamiq.com/support/faqs/browserconsole/
3. Copy paste the contents of wordleBreaker.js onto the console.
4. Initiate and run the wordle breaker by running the following commands one after another
```
w = new WordleBreaker();
w.break();
```
Voila! Now see the algorithm in action as it tries to crack the day's word.
