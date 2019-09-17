* Rule based AI systems can easily solve problems that are diffucult for humans to solve, but easy for computers. Think about math for extremely small or extremenly large numbers.
* The current challenge for AI is to achieve performance that surpasses human performance on tasks which are intuitive for humans but cannot formally be described in a rule based system. Recognizing friends for example.
* <b>Knowledge Base</b> approach to AI:
  * Hardcoding knwoledge about the world.
  * Example: <a href = "https://en.wikipedia.org/wiki/Cyc">Cyc.</a> It's an attempt to codify human common sense. Uses an inference engine for logical reasoning. Suffice to say that it is not very effective.
* This is why <b>ML - Machine Learning</b> came about. Computers need to figure out the rules on their own.
* ML depends heavily on <b>representations</b>. How data is presented to the system. Imagine a model with no feature engineering compared to a model that has extensively used feature engineering. We know that the latter will inevitably perform better for, say, logistic regression since the engineered features will be selected such that the model performs better. This is not to say that feature engineering is the end all-be all in ML. Deep Learing tries to do away with most of feature engineering. Just an example for edification.
* More on representations - comprehending pure Shakespearen English is way harder than comprehending colloquial English. This applies to computers as well. Data presented in a computer friendly format will give better results.
* Since we are trying to get computers to do our intuitive tasks for us, feature engineering cannot be useful in every case. It's hard to define features for an intuitive task. Example - Say we own a dog. How do we teach a computer to recognize that a certain dog is a friend? Classifying dogs is well and good. That narrows the search space into a certain kind of dog. What if two dogs of the same kind look eerily similar? Humans would just call upon their dog or recognize some behavior peculiar to their dog. Seems like calling upon your dog might be the only way. Probably a bad example, but the point is - it is hard to codify all the behavior that might pertain to a certain dog, since another dog can share that peculiarity. 
* <b> Representation Learning</b> - Using ML to discover the best representation  for a given task instead of feeding in a variety of representations to manually try to find the best one. Models are more adaptable and it takes less time than humans trying to find the right representations.
* <b>Autoencoder</b> - Think about multiplexing and demultiplexing. Think about a person who can only speak English trying to talk to a person who can only speak Japanese. We need to translate from English to Japanese (<b>Encoding</b>) and from Japanese to English (<b>deencoding</b>). Encoders encode data into a new representation and deencoders convert the encoded data back to the original representation. Representations preserve information from one form to another and also enable higher model performance.
* <b>Factors of variation</b> - These are simplifications which help make a prediction. Learning a new language, we usually translate the target language back to a language that we are comfortable with before responding in the language that we are learning.
* <b>Deep Learning</b> - Uses the same idea to build complex representations out of simple representations. <a href="https://cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf"> Visualizing and Understanding Convolutional Networks by Zeiler and Fergus</a> (Page 7 in the paper). We can clearly see that as we go deeper in the network, the model is learning more complex representations.
* <b>Multilayer Peceptron</b> - The very famous neural network. Cannot do a better job than <a href="http://neuralnetworksanddeeplearning.com/chap1.html">Neural Networks and Deep Learning.</a>
### Measuring the depth of a model:
* The length of an object depends on the scale of measurement.
* More granular measurements will give a higher length - 1m = 100 cm.
* Similarly, if we measure by simple operations we get a higher length than when we measure by the ruler of complex operations. Refer to pages - 7-8 in the book and figure 1.3.
* Two ways:
 1. Depth of computational graph: Longest path from inputs to outputs given a specific ruler say basic operations (addition, multiplication, functions).
 2. Depth of probabilistic modeling graph: Depth of the graph defining how the concepts are related to each other. The book gives a great example.

# Who Should Read the Book:
* The book has several diagrams which are great to determine the pre-requisites for a chapter, do check it out.
* Do read this section if you are confused about what to read in this book.
* For our purpose, we'll assume that we want to start a career in DL and AI research. 



  
