# Pose-audio

Another Hubert Sia and Nadia Abdul Aziz's fun project :)

Have you ever wonder that you can use your body pose to make sounds?

This is a Teachable Machine that detects different human poses. Each predefine poses manipulates the sound of the sythsizer.

We created on our own dataset by scanning our own pictures through https://teachablemachine.withgoogle.com/ . Letting the ML analyzing our pictures of our poses and classified them.

For this project is a combination of both ML and Tone.js for achieving the musical project.

Here are the different body position classification poses:

- T-Pose - Both arms up
- Left arm up - Left arm up (palm facing towards the camera)
- Right arm - Right arm up
- Squat - Bending the body or lowering the level when standing
- Idle - sitting or standing normally
- None - Absent
- Hidden - Covering the face with one hand

The model was trained on custom data from the webcam, as we were committed to not using external data, using between 54-300 images/examples per class in order to get the desirable results, several versions exist. We left all meta-parameters at defaults. 

Our strategy of developping the ML is too make sure we have a clear shot of the subject without any obstacles that could jeoperdize the pictures. 

It suffers is that depending on the lighting and the environnment, the detection struggles with background changes specifically as it misclassifies empty rooms into pose classes.

T-Pose and Squat are difficult to capture due to them being complex and farther from the camera. None and Hidden have some overlap as well a hidden is an incredibly narrow dataset. We are open to further explorations within this project, and regret not having the opportunity to refine the outcome further within the given timeframe.

Here is the live version online: https://hubertsia.github.io/pose-audio/
