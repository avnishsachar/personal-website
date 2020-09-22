+++ 
draft = true
date = "2019-05-01"
title = "Interview Prepration Web App"
slug = "interview-coach"
+++

  ![interview prepration app](/img/interview_coach.jpg)

We created a web app to help people prepare for interviews or public speeches through real-time feedback on their body movements, face emotions. In addition to this we provided a thorough analysis of their answers in terms of speech patterns and breaks in speaking flow after each session to help the speaker improve using the feedback.

Face analysis: We used the cognitive services Face detect api to extract emotion, smile, and posture data and feed it back to the frontend for notification feedback for the user.

Speech analysis: The speech analysis script will record the voice input and compute how much time the person was quiet and the speed of speech (words per minute). It uses azure services to get transcription of what the person answered so they can re-read it later.

Pose analysis: We used a Deep Neural Net model for performing Human Pose Estimation in OpenCV. The model predicts the posture of a single person in the frame and then checks if the person has a proper posture or not

This project was presented at the [Copenhacks'19](https://devpost.com/software/copenhack2019) hackathon held at the Microsoft Development Center, Denmark. We secured 3rd place for this submission!

