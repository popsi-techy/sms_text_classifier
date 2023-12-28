# sms_text_classifier
A neural network is a machine learning model inspired by the human brain. It consists of interconnected artificial neurons organized into layers. Neural networks are used for tasks like pattern recognition and decision making. They learn from data by adjusting the strength of connections (weights) between neurons. Deep learning involves neural networks with many layers, enabling them to learn complex patterns and representations from large datasets.

In this project, I created a machine learning model that will classify SMS messages as either "ham" or "spam". A "ham" message is a normal message sent by a friend. A "spam" message is an advertisement or a message sent by a company.

I created a function called predict_message that takes a message string as an argument and returns a list. The first element in the list should be a number between zero and one that indicates the likeliness of "ham" (0) or "spam" (1). The second element in the list should be the word "ham" or "spam", depending on which is most likely.

I used the SMS Spam Collection dataset. The dataset has already been grouped into train data and test data.
