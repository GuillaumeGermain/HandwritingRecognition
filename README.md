# HandwritingRecognition
A bit of fun with IOS and Machine Learning

This IOS App is based on a [youtube video](https://www.youtube.com/watch?v=bOg8AZSFvOc) explaining all the details.
I have added later some changes to experiment a bit.

Basically, the user draws a number on the drawing area, and this number will be recognized.
The picture is reduced to a 28x28 pixel picture.
This picture is then given to a neural network, which provides a list of probabilities for each number.(softmax).
This neural network is embedded in a CoreML file, which was got from here: 
[http://coreml.store/mnist](http://coreml.store/mnist)

As I tested it, the performance was actually average.
I tried several things to improve it, for instance increasing the thickness of the drawing line.
I also displayed the 28x28 picture on the top left to see how the picture given to the NN was distinguishable.
