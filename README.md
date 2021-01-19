# MarkovChains
Implementation of Markov Chain for generation of song lyric.

Pre-requisite:
  - Markov Chain : A Markov chain is a mathematical system that experiences transitions from one state to another according to certain probabilistic rules. The defining characteristic of a Markov chain is that the future states are dependent only on the present state and not on how the process has arrived at its present state.
   - Rationalization : Computation of probability of different future states for a particular present state in accordance with training data.
  
Implementation:
  - Present State -> Last 4 letters(labels) in the text.
  - Future State -> Letter to be generated.
  
Algorithm:
  - S1 -> Start
  - S2 -> Rationalization of training data
  - S3 -> Input of length constraint, present state of model (First 4 letters)
  - S4 -> Generation of labels on the basis of present state and updation of present state till length of text reaches the length constraints
  - S5 -> End
  
  Model Implementation: https://github.com/its7ARC/MarkovChains/blob/main/marcovChains.ipynb
  
  Training data: https://github.com/its7ARC/MarkovChains/blob/main/Apna%20time%20Aayega.txt
  
  Output of model: https://github.com/its7ARC/MarkovChains/blob/main/output.png
  
  
