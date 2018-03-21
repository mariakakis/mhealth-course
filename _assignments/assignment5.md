---
title: 'Assignment 5 – Gesture Recognition on an Android Phone with an Arduino'
nickname: 'A5'
assigned_class_index: 8
due_class_index: 10
summary: |
    In this assignment, you will be making a gesture detector like in Assignment 2. The machine learning part will still happen on the phone, just like before, but the sensing part will happen on the Arduino. The Arduino will be mounted on your body using the 3D printed part you made in Assignment 4. The accelerometer/gyroscope data should get transmitted from the Arduino to the phone and then processed to show the name of the predicted gesture on the phone. You are free to whatever code you want from earlier assignments.
optional: |
    Train your model in real-time so that your app can work on us, your instructors, without having us using the app beforehand. This means that your app will start with a blank model without any training data. There will be a button (or buttons) that we can hit to perform new gesture and assign labels to those gestures for training. On-the-fly, the model will train itself on that new data to create a personalized gesture model. After a "reasonable number" of gestures (5-10) per label, the model should be able to predict our gestures.
starting_materials: TODO
grading: |
    (60 points) We will briefly examine your code to ensure that you are using some form of machine learning to idenify which gesture is being performed. <br/>
    (40 points) You will perform each gesture 3 times with the phone in your hand. For full credit, your app must correctly identify at least 8 out of the 9 tries. -5 points for each extra mistake.
deliverables: |
    Source code (.zip, .tar, or GitHub link): <a href="https://canvas.uw.edu/courses/1131076/assignments/4143525" target="_blank">link</a><br/>
    In-class demo
---
