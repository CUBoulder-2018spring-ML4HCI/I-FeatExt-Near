I went with the Kadenze assignment description more than the one on the syllabus website -
this is because I did not have access to any of the sensors, and TouchOSC, after I downloaded
and tried to run it, did not send OSC messages reliably. For some reason, it worked with wekinator
but not with the weki input helper project.

Name: Stacia Near

Goals: Create a project that synchronizes a visual with a sound by using weki input helper
to extract the features of x velocity and y velocity of the visual. When the visual is moving 
faster, the sound should be higher pitched. When it moves slower, the sound should be low pitch.
This could have applications in gaming, where the sound a virtual car makes changes realistically
with its velocity.

Tools:
Wekinator
Weki input helper
Processing_FMSynth_3ContinuousOutputs
Simple_Mouse_DraggedObject_2Inputs

Accomplished: I successfully made a project in which you could drag the 2D cube from the wekinator package
and when the cube was moving faster, the sound would increase in pitch as planned.

ML Choices: I attempted to use linear regression, but it was too simple a solution to deal with 
the complexity of accounting for both x and y velocity being fast or slow. Linear regression resulted
in almost no change in the sound when the speed changed.
I ended up using a neural network, which reliably understood how to change the sound when the velocity changed.
It sounded very close to how it did in training.

Link: https://github.com/CUBoulder-2018spring-ML4HCI/I-FeatExt-Near.git
