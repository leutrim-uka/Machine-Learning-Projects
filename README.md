# Machine-Learning-Projects
In this repo, you'll find projects of varying levels of complexity on Computer Vision, NLP, and other Machine Learning problems.

<hr/>
<h2> Computer Vision </h2>
<img align='left' src="https://github.com/leutrim-uka/Machine-Learning-Projects/assets/67911249/2266f2d5-0c87-4918-8f85-1df1d45ab439" height=120 width=120>

<h3>Digit recognizer with Feed-Forward NNs and CNNs</h3>
This is the classical computer vision task, in which we recognize handwritten digits from the MNIST dataset.
The solution is built using Keras (for the Feed-Forward NNs) and PyTorch (for the CNNs) <br/>
<a href="https://github.com/leutrim-uka/Machine-Learning-Projects/blob/main/computer_vision/digit-recognizer-pytorch-keras.ipynb" target="_blank">Go to project on GitHub</a>

<h3>Simple Autoencoder</h3>
In this project, I implemented a simple autoencoder architecture using convolutional layers and trained it on the MNIST dataset. The encoder part of the network
compresses the images by lowering the resolution layer by layer until it reaches the bottleneck. The decoder part then attempts to reconstruct the image back to 
the original resolution, but it introduces some blurriness.
<a href="https://github.com/leutrim-uka/Machine-Learning-Projects/blob/main/computer_vision/autoencoder.ipynb" target="_blank">Go to project on GitHub</a>

<hr/>
<h2> Natural Language Processing </h2>

<h3>Named Entity Recognition in court documents using BERT</h3>
<img align='left' src="https://github.com/leutrim-uka/Machine-Learning-Projects/assets/67911249/19b06c97-3532-4706-9274-3f8570c5b525" height=120 width=120>

The goal of this project was to build a model that is able to process court documents and recognize various named entities, such as judge names, defendants, locations, dates, and so on. The training data was intially in JSON format, and the labels were provided as indexes indicating the starting and ending positions of the named entities in the sentence. I converted them to the IOB tagging format (Inside-Outside-Beginning), which is required by BERT. As seen in the results, the model was able to recognize some entities with more confidence, while it had difficulties distinguishing some rarer entities in the dataset. Disclaimer: I worked on this project prior to learning some crucial Machine Learning concepts, it needs to be revisited and improved.
<a href="https://github.com/leutrim-uka/Machine-Learning-Projects/tree/main/NLP/NamedEntityRecognition_CourtDocuments" target="_blank">Go to project on GitHub</a>
