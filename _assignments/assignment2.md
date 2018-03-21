---
title: 'Assignment 2 - Gesture Recognition on an Android Phone'
nickname: 'A2'
assigned_class_index: 3
due_class_index: 5
summary: |
    You will build an Android app that uses the accelerometer and/or gyroscope to disgtinguish between 3 different hand gestures when the phone is held facing up in your hand: (1) palm up-to-palm down, (2) palm down-to-palm up, (3) pushing the phone away from your body. You could easily distinguish between these gestures using signal processing and heuristics like in Assignment 1; however, we want you to use machine learning this time around. Here is the step-by-step plan that you will likely want to follow:
    <ol>
    	<li>Collect a few examples of each gesture
    	<li>Come up with features that summarize the gestures in a manner that makes them easy to distinguish (hint: the first two gestures involve rotating the phone while the third gesture does not, so you will want at least one feature that captures the notion of rotation)
    	<li>Train a classification model offline on the data you collected
    	<li>Save the model on the phone and have the app show the prediction of new gestures on the screen.
    	<li>Try out your model by performing some of the gestures again. If your app is not predicting correctly, you may need to consider new features, more training examples, or a different model.
    </ol>
optional: |
    Train your model in real-time so that your app can work on us, your instructors, without having us using the app beforehand. This means that your app will start with a blank model without any training data. There will be a button (or buttons) that we can hit to perform new gesture and assign labels to those gestures for training. On-the-fly, the model will train itself on that new data to create a personalized gesture model. After a "reasonable number" of gestures (5-10) per label, the model should be able to predict our gestures.
starting_materials: TODO
grading: |
    (60 points) We will briefly examine your code to ensure that you are using some form of machine learning to idenify which gesture is being performed. <br/>
    (40 points) You will perform each gesture 3 times with the phone in your hand. For full credit, your app must correctly identify at least 8 out of the 9 tries. -5 points for each extra mistake.
deliverables: |
    Source code (.zip, .tar, or GitHub link): <a href="https://canvas.uw.edu/courses/1131076/assignments/4143517" target="_blank">link</a><br/>
    In-class demo
---
