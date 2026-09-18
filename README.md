### Training Models to Classify the CIFAR Dataset and Comparing Performance

<p> This is a simple implmentation of an experiment pipeline with the CIFAR image dataset using Jupyter notebooks, PyTorch and MatPlotLib. It's nothing special, but puts together a couple of things that will let me do a lot more quite quickly now I've got it all down. The general purpose is to quickly get myself up to scratch on model testing and underlying concepts, and if anyone ever comes across this maybe it'll help you if you're just starting out. Both models are also in this repository as well as their test results in the models/ and logs/ folders respectively.</p>
<br>

<br>
The differnce of this program from the simple PyTorch tutorial network is that two models are created and trained - a model that isn't meant for this at all (a simple linear/ReLU stack based off the PyTorch tutorial for the MNIST dataset) and a model composed of image recognition layers - convolutions. 
Both of these models get trained for the same number of epochs on the test sets and their accuracies and loss' are recorded in CSV format. 
The accuracies' of both models' classification abilities are then shown in a simple matplotlib line graph showing the benefits of visualisation.