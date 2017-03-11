# MathematicaChatbot
a simple chatbot written in Wolfram's Mathematica

The process works by generating two Markov chains: one in which the bot stores examples of text that classifies as human, and another which stores non-human speech. If given a negative reaction, the bot will classify its previous response as non-human.

Responses are generated with very rudimentary analysis of the structure of the English language. **There is no natural language processing done.**

Responses are given using the following call:
Mathematica
```
respondTo[someString];
```

Example human responses are included in this project. Bot responses will be generated automatically, assuming the file exists. For our purposes, we had approximately 10 minutes of conversation fed to the bot. We also used Shakespeare’s Hamlet and received very interesting responses.