# Binary Classification
- Logistic Regression is an algorithm for binary classification.
- E.g <br> <b> Input: </b> Image of a cat (3 vectors of all the pixels, i.e. Red Green Blue) <br>
<b> Output: </b> 1 (cat) vs 0(non cat)

### Notations:
- (x, y), x is element of R^(nx * m), y is element of {0, 1}
- m training examples: (x1, y1), (x2, y2), ..., (xm, ym).
- mtraining is the # of training set, and mtest is the # of testing set.
#### A more compact notation:
- X = [x1, x2, x3, ..., xm]
- X has m columns (m = training examples), and nx rows.
- Sometimes you see the Xs the other way around, however our convention will make the implementation much easier.
- In Python, <b> X.shape </b> is for finding the shape of the matrix, it will be <b> (nx, m) </b> .
- Y = [y1, y2, y3, ..., ym]
- Y is an element of <b> R^(1 * m) </b> .
- Similarly, <b> Y.shape = (1, m) </b> .
