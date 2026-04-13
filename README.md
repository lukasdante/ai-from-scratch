# AI From Scratch

This is a repository where I compile all of the algorithms that are related to artificial intelligence that I have written **from scratch** over the course of studying it. 

## Contents
```
├── a-star
├── mlp
├── naive-bayes-spam-filter
└── README.md
```

1. `a-star` is just a basic implementation of the A* search algorithm for the 8-puzzle problem using misplaced tiles, Manhattan distance, and Nilsson's sequence score as the heuristic functions. It follows the pseudocode provided in the class I attend about heuristic search.

2. `mlp` is a multi-layer perceptron implementation where I programmed the forward pass and backpropagation from scratch from the math I learned in class. investigated how learning rate and momentum coefficient affect model convergence. I simply used two layers where I perform hyperparameter tuning to identify the best model for multi-class classification task.

3. `naive-bayes-spam-filter` is an implementation of the Naive Bayes classifier in identifying if an email is either solicited or unsolicited. I implemented Lambda smoothing, and performed hyperparameter tuning on different Lambda values. I also used mutual information to limit model size parametrically given the top k words.

