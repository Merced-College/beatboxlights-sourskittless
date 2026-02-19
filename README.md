[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22734763)
# BeatBoxLights
this is your README.md file, make sure to edit it and put your names, the date, and the answers to the lab and reflections questions here.

Group: Santiago Jimenez, Adrian Amezcua, Genisa Salinas


# Step 1 Reflection:
What was your baseline value in a quiet room?

  Our baseline value in a quiet room was 705.

Why do we update baseline slowly instead of setting it directly to raw?

  We update baseline slowly instead of setting it directly to raw to account for background noise. This gives us a more accurate baseline value.

What would happen if baseline updated too quickly?

  If baseline updated too quickly we would get a less accurate baseline value since it would be skewed by sudden loud noises or constant background noise.

# Step 2 Reflection
Why does LightUp not know anything about microphones?

  The Lightup does not know anything from the microphones beacasue they function indepedently of each other.

What design principle does this demonstrate?

  This demonstrates the design principle of encapsulation in Object Oriented Programming which puts the functions and variables belonging to the lights in
  its own class, LightUp. This is kept separate from the the functions and variables that pertain to the microphone. It also demonstrates decoupling because we can
  alter our Lightup class and Microphone class easily since they are kept separate from each other.

If you wanted to change to 10 LEDs, what would need to change?

You would have to make an array for 10 integers instead what the current one is. 

# Step 3 Reflection
What happens if cooldown is removed?

  It would always return true when removing cooldown.

What happens if threshold is too low?

  If threshold is too low then it can produce a true statement without any noise ocurring.

Why is time (millis()) important in embedded systems?

  It allows you to see if the LED light stay on during whatever duration specified.

# Step 4 Reflection
How does intensity affect the sound?

  It can make the noise sound higher with also making it last longer. 

Why is tone() sufficient for this lab instead of playing WAV files?

  It may require less memory usuage which results in a faster computation since tone() is a built in function.

# Step 5 Reflection
How is std::vector used in this system?

  It stores new values while removing old values. Also when baseline needs to be calculated it gets the data from the vector.

What does smoothing accomplish?

  Smoothing is what is considering all the background noise.

What would happen if smoothing was removed?

  If smoothing was removed then it would pick up any little noise which will make the LED's turn on.

