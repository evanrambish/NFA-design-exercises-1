# NFA Design Exercises 1

I completed Problems 6–10 using JFLAP and tested each NFA with accepted and rejected binary strings.

## Problems completed

- Problem 6: Strings that start with `10`
- Problem 7: Strings that end with `10`
- Problem 8: Strings that start with `01` and end with `10`
- Problem 9: Strings that contain the substring `10`
- Problem 10: Strings that do not contain the substring `10`

## Learning summary

Problem 8 had given me the hardest time since the NFA has to recognize both beginning and ending conditions. The string `010` was useful since the `01` in the beginning and the `10` in the ending overlap nicely.

I asked questions to ChatGPT about the difference between NFAs and DFAs and how nondeterministic branching works.

The main thing that I learned doing this is that every single possible transition has to be considered. For the future, when I do state-controller or compiler problems, I will make sure to write out every possible current state after each input symbol and test some short, typical, or misleading strings.