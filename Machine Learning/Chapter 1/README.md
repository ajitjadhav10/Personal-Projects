**Definition:** Machine Learning is defined as a field of study that allows computers to learn without being programmed explicitly

Machine Learning system can be classified as follows:
  - Whether they are trained by a human or not(supervised, unsupervised, semi-supervised, and reinforcement learning).
  - Whether or not they can learn incrementally on the fly (online vs batch learning).
  - Whether its are instance based vs model based learning.

Let's take a closer look at each of the them:

**1. Supervised Learning**: In Supervised learning we have to feed the algorithm with training data which contains the desired solutions called labels too. 
eg 1: In case of a spam filter, you'll need to feed the algorithm with example emails with their class(ham or spam) and based on that it learns to classify new emails as either ham or spam.
eg 2: 

Some important supervised learning algorithms are:
- k-Nearest Neighbors
- Linear Regression
- Logistic Regression
- Support Vector Machines (SVMs)
- Decision Trees and Random Forests
- Neural networks

**2. Unsupervised Learning**: As the name suggests, here the data is unlabelled and system learns on its own

Some important unsupervised learning algorithms are:
- Clustering: As the name suggests, it means grouping of similar data
- Visualization and dimensionality reduction:
  - Visualization algorithms give a 2D or 3D representation of your data
  - Dimensionality reduction groups data which is similar to each other in order to simplify the data.
- Anomaly detection
- Association rule learning: Here goal is to dig into the data find interesting relations between different attributes of the data. Eg. if you own a supermarket association rule can help you understand from your sales as to which products are often bought together, so based on that those items can be placed closer together.

**3. Semisupervised Learning**: In this case, the training data contains a lot of unlabelled data and some labelled data. Such a case is called semisupervised learning.
Eg: Google photos, where you enter the name of a person(label one photo) in photo and then google photos recognizes all other photos of that person.

**4. Reinforcement Learning**: Here the system which needs to learn, is called an agent. The agent can observe the environment and perform actions, based on those actions the agent gets rewards or penalties(if the action performed is not the desired one). The agent has to figure out what is the best strategy(called policy).
Eg. AlphaGo, it is a program that learned how to play the game Go by observing millions of games and then by playing many games against itself.



**5. Batch and Online Learning:**
In **Batch learning**, the system is trained on the avaiable data and then it is used. Since training takes a lot of time and requires large amount of data, it is generally done offline. In this case the system doesn't continue learning when it is being used. Hence, if we need to train the system with an updated data, we'll need to train the system from scratch, then discontinue the old system and replace it with the new system. Hence, this should be avoided where systems need to learn from new data continuously.

In **Online learning** the system is continuously trained on small batches of data(it is also called incremental learning). This is preferred for systems where there is continuous flow of data.(eg. stock prices) and there is need of adapting to changes rapidly. An important factor here is **learning rate**, if it is set to 'high', then the system will rapidly learn from new data and forget the old data and if it set to 'low' it will learn more slowly and it'll be less sensitive to noise. A challenge that arises here is if bad data is fed to the system, then the performance of the system will gradually decline. To be safe from this, we need to continuously monitor the system and switch off learning when we notice a drop in performance.


**6. Instance based vs Model based**
I'll explain **Instance based** system with an example, a spam filter can be programmed to flag emails that contain words which have been previously found in other spam emails. This requires, a measure of similarity between two emails. This is called as instance based learning: the system learns the examples by heart, then generalizes to new cases using a similarity measure.

Another way to do this is, through **model based learning** where you create a model using your set of examples and then use that model to make predictions.
Eg. Say, if we want to see whether money makes people happy or not, we can do this using better life index from oecd's website as well as GDP per capita from IMF's website. By analyzing we realize that there is a 'linearly increasing' trend, hence we can model life satisfaction as a linear function of GDP per capita. This what we have done here is called model selection. Now, we'll use this model to make predictions.
