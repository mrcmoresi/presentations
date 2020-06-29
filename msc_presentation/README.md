# MSc Presentantion [in Spanish]

Title: Automatic modeling of learning paths: When to generate personalized help for beginners programmers?

Abstract: Understanding which is the path that a student takes when using a web-based coding tool would allow a teacher to make decisions based on evidence.
However, analyzing such data by hand would be prohibitively expensive, and the teacher feedback would probably arrive too late. The automatic modeling of educative data with machine learning techniques promises a better understanding of the behaviour and knowledge about student. 
For this work we have a dataset provided by Mumuki, an online teaching system. This thesis proposes a way to automatically model when a student is at risk of leaving an exercise and needs personalized help. Based on a pedagogical theoretical framework we automatically design and extract from the dataset  representative  features to model the path of students comparing formal and informal education environments.
We trained several machine learning models comparing their performance in this task. 
Finally, with the aim of imitating the sequentiality of solving a programming exercise task, a recurrent neural network was trained in this same task. After this, a comparison between models was made to try to determine which is the best option for this task.
The result of this thesis is a comparison between a simple sequential neural model and a concrete proposal of feature engineering for the task, in order to model automatically the path of the students. The models were built based on the data generated in the Mumuki system.
It was possible to build a linear model, fast to train, with similar performance obtained with a more complex model such as a neural network.
