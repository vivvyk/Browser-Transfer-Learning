# Authors
Vivek Kumar (vk2425)

# Browser Based Transfer Learning
An application for image classification which brings state-of-the-art machine learning algorithms to the public. This is accomplished using tensorflowjs and transfer learning.

# Files
Importantly, see index.js.
Sample data can be found in bb-sb_data.

# Running
To run this website locally, run in the directory containing index.html (REQUIRES PYTHON 3):

`python -m http.server`

Observe the hosted location and port, often localhost:8000, and navigate to this in a browser.
Alternatively, you can access the hosted website at http://accessible-transfer-learning.s3-website-us-east-1.amazonaws.com/

# Instructions
1. Click the add class button to add as many classes as you like.
2. For each class, choose some pictures (only a few are required). You can also take these pictures if you have a mobile phone.
3. Click the train button (you can change the epochs before you run).
4. Load an image for prediction with the load button.
5. Press the predict button to observe the trained classifier work.

# Evaluation Metrics
In terms of our project, we first evaluated our model based on actual data on a standard dataset like the Kaggle Flowers Dataset. Given MobileNet's high performance, we were unsurprised with high accuracies in the 90s.

What's more important is the performance on the job. As seen in our presentation, we tried taking photos with our phones and evaluating the classifier in our browsers! We found we could classify objects around us, even people!
