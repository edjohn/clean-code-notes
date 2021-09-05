# Chapter 2: Meaningful Names

### Use Intention Revealing Names
- The name of a variable, function, or class should tell you **why it exists, what it does, and how it is used**.
- If a variable requires a comment, then the name does not reveal intent
  - `int d; //elapsed time in days` 
    - Bad Practice, does not reveal intent
  - `int elapsedTimeInDays;`
    - Good Practice

### Avoid Disinformation
- Avoid leaving false clues that obscure the meaning of code.
  - `hp` or `aix` or `sco`
    - Bad Practice, names are already associated with Unix platforms or variants
- Avoid words whose entrenched meanings vary from our intended meaning.
  - `accountList`
    - Bad Practice, misleading if variable is not a list
  - `accountGroup` or `bunchOfAccounts` or `accounts`
    - Good Practice

- Beware of using names which vary in small ways.
  - `XYZControllerForEfficientHandlingOfStrings` and `XYZControllerForEfficientStorageOfStrings` have similar shapes
  - Spelling similar concepts similarly is information, but using inconsistent spellings is disinformation
  - Due to features like auto-complete, it's beneficial to have similarly named things grouped together alphabetically while still having obvious differences


### Make Meaningful Distinctions
- Avoid number-series naming
  - `a1` and `a2`
    - Bad Practice, names are noninformative
  - `source` and `destination`
    - Good Practice

