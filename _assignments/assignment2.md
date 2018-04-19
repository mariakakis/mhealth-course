---
title: 'Assignment 2 - Gesture Recognition on an Android Phone'
nickname: 'A2'
assigned_class_index: 3
due_class_index: 5
summary: |
    You will build an Android app that uses the accelerometer and/or gyroscope to disgtinguish between 3 different hand gestures when the phone is held facing up in your hand: (1) palm up-to-palm down, (2) palm down-to-palm up, (3) pushing the phone away from your body. You could probably distinguish between these gestures using signal processing and heuristics like in Assignment 1; however, we want you to use machine learning this time around. Here is the step-by-step of how the app will work:
    <ol>
    	<li>The app will collect a few examples of each gesture
    	<li>You will compute various features that summarize the gestures in a manner that makes them easy to distinguish (hint: the first two gestures involve rotating the phone while the third gesture does not, so you will want at least one feature that captures the notion of rotation)
    	<li>The app will train a classification model offline on the data you collected
    	<li>You should then be able to perform one of the gesture again and have the app correctly identify which one you performed. If your app is not predicting correctly, you may need to consider new features, more training examples, or a different model.
    </ol>
grading:
- (50 points) We will briefly examine your code to ensure that you are using some form of machine learning to identify which gesture is being performed.
- (50 points) You will perform each gesture 3 times with the phone in your hand. -5 points for each mistake.
<!-- extra_credit:
- (+up to 10 points) Come up with your own set of gestures that your model can distinguish. The more complicated the gestures are, the more points you can earn. You can extend the duration of the gesture recording for different gestures.
- (+5 points) Your demo can work on both yourself and one of the instructors. -->
starting_materials: |
    Starter code: <a href="https://github.com/atm15/Assignment2Starter" target="_blank">link</a><br/>
deliverables: |
    Source code (.zip, .tar, or GitHub link): <a href="https://canvas.uw.edu/courses/1131076/assignments/4143517" target="_blank">link</a><br/>
    In-class demo
---
