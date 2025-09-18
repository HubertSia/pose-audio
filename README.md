# Pose-audio

Another Hubert Sia and Nadia Abdul Aziz's fun project :)

Have you ever wonder that you can use your body pose to make sounds?

This is a Teachable Machine that detects different human poses. Each predefine poses manipulates the sound of the sythsizer.

We created on our own dataset by scanning our own pictures through https://teachablemachine.withgoogle.com/ . Letting the ML analyzing our pictures of our poses and classified them.

For this project is a combination of both ML and Tone.js for achieving the musical project.

Here are the different classification poses:

- T-Pose
- Left arm up
- Right arm up
- Squat
- Idle
- None
- Hidden

The model was trained between 54-300 images/examples per classes in order to get the desirable results.


Our strategy of developping the ML is too make sure we have a clear shot of the webcome of our poses without any obstacle that could jeoperdized the pictures. Making sure that the webcam has a full image of the body and hand.

Some of the flaws it suffers is that depending on the lighting and the environnment, the detection might be working sometimes but in a 100% rate that we initially thought.

T-Pose and Squat are the must difficult to capture due to them being a bit more complex to capture and required more pictures and data in order to succeded. Even None and Hidden has some difficulty to recognize too as well. At the end, it need it more data/pictures and making sure that we were somehow isolated to get it right

It was quite a challenge to achieve good performance due on how diffirent  the human being bodies are, it was quite difficult for the ML to learn it at a snap. 

Initally, 

Here is the live version online: https://hubertsia.github.io/pose-audio/
