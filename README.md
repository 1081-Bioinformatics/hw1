# hw1

## Description

* Writing R script to generate PAM250 from the given mutation probability matrix.
* PAM250 must be as a log odds and complete square matrix, not the format of the given mutation probability matrix.
* Creating your own R script, hw1_yourStudentID.R , ie. hw1_105753026.R, to read mut.txt and output pam250.txt.
* [HINT] PAM250 is a symmetric matrix even the given mutation probability matrix is not.

## File

* hw1_ref.R: You can start from this reference code, and try to write your own comment in English
* pam1.txt: Point Accepted Mutation Matrix

## Command

Executing your code with the following command.

```R
Rscript hw1_studentID.R input_path_pam1.txt output_path_pam250.txt
```

## Evaluation
* works for input & output right PAM250: 90

### Bonus

* Preprocess PAM1: +2
* Post-process PAM250: +2
* Correct output format: +2
* Output without quotation marks "": +2
* Round to the nearest integer number: +2

### Penalty

* Use the fixed path inside your code: -1
* Calculate with the wrong number of loops: -1
* High code similarity to others: YOUR SCORE = 0
