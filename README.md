# nict-jle

An adapted version of the NICT-JLE corpus for use with disfluency detection models. Files are split into train, heldout and test sets with a balanced distribution of learner level types. 

Each dataset contains the following information: 
  - File number
  - Word
  - POS tag
  - Disfluency tag 1 (incremental)
  - Disfluency tag 2 (BIOES)
  - Learner proficiency level
  - Activity type and topic: conversation, roleplay or picture description task
  - Whether the word had preceding short or long pauses
  - Whether the word had preceding non-verbal laughter 
  - Whether the word itself was laughed
  - For the test set only: whether the word had a preceding error label. (Please note that errors that occur during the reparandum phrase are not labelled.)
