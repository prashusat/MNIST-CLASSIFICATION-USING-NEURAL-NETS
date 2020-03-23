<h1>TASK:</h1>

Train a fully-connected net for MNIST classification (sorry, no CNN please,
yet). It should be with 5 hidden layers each of which is with 1024 hidden units. Feel free to use whatever techniques you learned in class. You
should be able to get the test accuracy above 98%.

<br/><br/>

Once you’re done with training, as a starter, do a feedforward step on your
test samples, a thousand of them. Capture the output of the softmax layer,
which will be a 10-dim probability vector per sample. In other words,
each output dimension has 1,000 predictions corresponding to the 1,000
examples. For each 10-d output vector, find the dim with the maximum
probability (which will eventually decide the class label). Plot the input
image associated with that in a grid of subplots. For example, you can
create a 10 × 10 grid of subplots, whose first row plots first ten input
images that produced the highest probabilities for the first dim (which
corresponds to “0”). Eventually, if your classification was near perfect,
you’ll see ten 0’s in the first row, ten 1’s in the second, and so on.
