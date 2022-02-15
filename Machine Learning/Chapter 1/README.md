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

**4. Reinforcement Learning**: Here the system which needs to learn, is called an agent. The agent can observe the environment and perform actions, based on those actions the agent gets rewards or penalties(if the action performed is not the desired one) The agent has to figure out what is the best strategy(called policy).
