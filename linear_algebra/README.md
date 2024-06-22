# Notes for linear algebra

### Linear Regression
#### Uses Supervised Machine Learning
Linear regression: Find the line of best fit corresponding to the data
Since linear regression is supervised the algorithm has the inputs and outputs
Suppose you are looking at the outputs on a graph linear regression would be
![aimeos-frontend] (https://miro.medium.com/v2/resize:fit:640/1*LEmBCYAttxS6uI6rEyPLMQ.png)
y = wx + b
w = weight
b = bias
y = y-axis
x = x-axis
Goal is to find the best w and b that fit the data

If multiple inputs equation is:
y = w1x1 + w2x2 + w3x3 ... wn+xn + b
1 input is 2d 2 is 3d ..... n is nd
d = dimension

System of Linear Equations(Matrix?):
(w1x1 + w2x2 + w3x3 ... wn+xn + b = y)(1)

(w1x1 + w2x2 + w3x3 ... wn+xn + b = y)(2)

(w1x1 + w2x2 + w3x3 ... wn+xn + b = y)(3)
            .
            .
(w1x1 + w2x2 + w3x3 ... wn+xn + b = y)(m)

(1), (2), (3), (m) = superscripts

Another way of writing the system of linear equations:
[w1 w2 w3 ... wn]  [x1(1) x2(1) x3(1) .... xn(1)] [y(1)  y(2)...y(m)]
vector of weights  [x1(2) x2(2) x3(2) ... xn(2)]        vector
                   [x1(3) x2(3) x3(3) ... xn(3)]
                        .
                        .
                   [x1(m) x2(m) x3(m) ... xn(m)]
                            matrix

weights are consistent throughout the column(vertical)
features are the numbers being multiplied by the weights(x)
Targets are the output

System(singluar or non-singular)
Singular System = Redundant or Contradictory Infinite Solutions or No Solutions
Non-Singular System = Complete(no redundant or contradictory information) One Solution
Rank is the measure of how redundant a system is

Linear Equaiton: 2a + 3b = 15 (straight line)
Non-Linear anything other than a linear equation. (not a straight line?)

