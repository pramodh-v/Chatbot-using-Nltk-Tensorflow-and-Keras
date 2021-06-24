# Chatbot-using-Nltk-Tensorflow-and-Keras
I have created a chatbot from scratch using the nltk,tensorflow and keras libraries.
The nltk library is used for incorporating nlp functions whereas the tensorflow and keras libraries are used for building the ANN.
The Keras-Tuner library is used for tuning and finding the best hyper parameters for the ANN model.

Accuracy in training set – 0.9937<br>
The possible patterns and responses are stored in a json file called ‘intents’.
I made this project completely on google colab as it brings the ease of using GPU’s with it.
# Use Cases:
The world is moving fast towards artificial intelligence and automation. Automating the process of interacting with users providing optimal solutions is a new innovation on the same.Chatbots come in real handy being useful in different aspects.
Some of its useful aspects are:

i) Reducing Labour,<br>
ii) Increasing efficiency in seller-customer interactions,<br>
iii) Spontaneous service,<br>
iv) Handling different situations concurrently.<br>
# Goals to be achieved:
i) To achieve complete automation of customer support.<br>
ii) Aligning sellers with customers’ needs (Product recommendation etc..) 
# Requirements:
  The libraries required are provided in the ‘requirements.txt’ file.
  Run the code:
  ```
  python –m pip install –r requirements.txt
  ```
  to install the aforementioned libraries.
# How to run?
  To run in google colab, installation of libraries is not required. Just running the respective cells will do.
  To run in jupyter notebook, install the libraries and run the cells in succession.
	To run in a separate python script, install the libraries and run the given code. 
	While running the chatbot cell, type ‘quit’ to stop running the process.
# Implementation Screenshots:
 ![image](https://user-images.githubusercontent.com/62897899/123304559-b10b6480-d53c-11eb-880f-2c3c7805e835.png)
 ![image](https://user-images.githubusercontent.com/62897899/123304580-b7014580-d53c-11eb-8cce-03ec39c0f07e.png)
 ![image](https://user-images.githubusercontent.com/62897899/123304596-bbc5f980-d53c-11eb-864a-78adcc7bc4fd.png)
# References:
https://www.tensorflow.org/api_docs - Tensorflow Documentation<br>
https://keras.io/getting_started/ - Keras Documentation<br>
https://keras.io/keras_tuner/ - Keras Tuner Documentation<br>
https://www.nltk.org/ - Nltk Documentation<br>
https://pypi.org/project/colorama/ - Colorama Documentation<br>
https://www.youtube.com/watch?v=1lwddP0KUEg&t=360s – To get a basic idea on implementation.<br>
https://www.youtube.com/playlist?list=PLZoTAELRMXVPGU70ZGsckrMdr0FteeRUi – For implementing ANN model and Hyper-parameter tuning.<br>
https://github.com/keras-team/keras-tuner/issues/181 - For Saving Best Model.<br>
# Conclusion:
  This project can be further implemented as a website with back-end technologies (preferably Flask) and also changing the intents.json file such that better accuracy and interactivity can be achieved.

