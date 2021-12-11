# SD201-project

In this project, we set to make produce recommendations to users of the Instacart online grocery
shop by mixing supervised machine learning methods trained on time features and by refining them
using association rule mining. We use a data set from Kaggle: link Our main question is: can we
refine a standard classification algorithm using association rule mining?
Key points from the data set:
• 3M anonymised grocery store orders
• 200,000+ Instacart users
• 4 to 100 orders for each user, timestamped
It is important to note that the competition’s goal and the goal of this project are different. The
competition’s goal is to predict the next basket of a client given their history of past orders. The
predicted cart should only have products that have already been ordered by a user. By contrast,
there is no restriction on the items that are in the predicted cart for my approach.
This is a multilabel classification problem, which is inherently harder than standard classification
problems and requires specific methods that we explore in the notebooks.
