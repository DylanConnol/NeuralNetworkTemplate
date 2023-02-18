# Neural Network Class
Pretty straight forward; essentially a blank custom coded neural network 
for ML programming. 

It only uses numpy as an import, the rest is custom coded. 

The class has many different layers. It is based off of this article:

https://towardsdatascience.com/backpropagation-the-natural-proof-946c5abf63b1

However, in this article, the code didn't seem to work for
me. So I rewrote it with the same derivatives and calculus 
to get it to function better.

The neural network right now only has the activation function for sigmoid. 
This is going to be expanded later, but so far this is the only one I could
get to work. ReLu didn't seem to converge with my program, but this is going
to be implemented soon. Ditto with softmax.


The class has multiple pretty self explanatory functions. There is the backprop
function, forwardprop function (to actually get an ouput!), gradient descent,
etc. The functions should have generics to help guide what the input expects.



