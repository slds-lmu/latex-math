# latex-math

The notation and shortcuts used in latex-files of lectures, papers, ... of the Working Group Computational Statistics is defined and maintained in this repository. 
Notation & shortcuts are splitted into multiple files depending on subject and can be integrated as needed. 

+ basic-math: basic mathematical notation such as mathematical spaces, sums & products, linear algebra, basic probability and statistics
+ basic-ml: basic machine learning notation such as notation for data (x, y), prediction functions, likelihood, loss functions, generalization error
+ ml-bagging
+ ml-boosting
+ ml-mbo
+ ml-nn: neural networks
+ ml-svm: support vector machines
+ ml-trees

## Using the notation
- Clone this repository into the main directory of your repo.
- Add latex-math to the gitignore file. 
- Add \input{../latex-math/\*}, for every file /\* you need to the preamble of your (TeX/Rmd) file.

## Updating / adding files
- A new shortcut / notation that falls into the scope of one of the existing files should be added in the respective file with a short description.
- Multiple shortcuts / notations belonging to another major subject should be summarized in a new .tex file. 
- **ALWAYS** check if a command is already contained in one of the files - overwriting a command might result in compiling errors.  
