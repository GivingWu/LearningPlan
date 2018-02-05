
# Machine learning

> Learning Map

## Supervised Learning（监督式学习） - Learning from teacher.
需要 input 大量的 Traning Data 去训练 output = label，But sometimes it is hard to callect a large amount of labelled data.

### Regression
Regression problem it output a scalar by input classification.

+ Stock Market Forecast
+ Self-driving Car
+ Recommentdation
+ Estimating the Combat ower(CP) of a pokemon after evolution

Step 1: Model
  Model = A set of function
  Linear model: y = b + ∑w(i) * x(i)
    // x(i): an attribute of input x (feature)
    // w(i): weight
    // b: bias
  y = b + w * x(cp) (w and b are parameters can be any value)
  f1:y = 10.0 + 9.0 * x(cp)
  f1:y = 9.8 + 9.2 * x(cp)
    ... infinite

Step two: Goodness of Function
  Loss function L:
    input: a function, output: how bad it is
    L(f) = L(w, b)

  Pick the 'Best' Function
  f* = arg min L(f)
  w*, b* = arg min L(w, b) // Gradient Descent

Step three: Gradient Descent
  learning rate


### Overfitting

// ¡™£¢∞§¶•ªº–≠œ∑´®†¥¨ˆøπå∂ƒ©˙∆˚¬…æΩ≈ç√∫˜µ


### Classification

1. Regression
2. Trainning Data(model)
  1. linear model
  2. non-linear model
    1. Deep learning - input/output pair of target function
    2. SVM
    3. decision tree
    4. K-NN

### Structured Learning - Beyond Classification
`input` - `function` - `output`

## Seme-supervised Learning


## Transfer Learning


## Unsupervised Learning


## Reinforcement Learning - Learning from critics.
Reinforcement Learning 是无法进行 supervised learning 的情况下使用的。

Alpha Go is supervised learning + reinforcement learning.