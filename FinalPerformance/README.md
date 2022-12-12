**Robot Joy Documentation**
===================





**Production Assignment**
===================

[Here](https://youtu.be/xKKcqtg8Xsc) is the video

In this speech assignment, along with the soccer commentary clip we chose, we tried to make our robot imitate a soccer player's movements, such as breaking through, scoring, and celebrating. Since we finished coding the Hobby RC program last week, we spent time practicing the remote control this week to make it better match the timing of the speech. The biggest difficulty we encountered was that the steering with the knob was rather counterintuitive and had a delay between our manipulation and the robot's movement. Our programmed rule is that when the value of AnalogRead of the knob is very large (when the knob is turned forward to the end), the robot goes left, and when the value of AnalogRead is very small (when the knob is turned backward to the end), the robot goes right. This is not an ideal way of operation because it is not intuitive enough and thus can not be operated with smooth steering (because we also need to simultaneously control forward/backward direction and the speed). Additionally, because forward and backward are also operated with another knob, we sometimes get confused and make mistakes.
