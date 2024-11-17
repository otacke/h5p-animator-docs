# H5P.Animator: Player
_H5P.Animator_ is a tool you can use to create simple animations. It does not compete with highly sophisticated tools like Blender or After Effects, but rather on the level of what many people do with PowerPoint. It is based on the [H5P](https://h5p.org) framework.

The animation player is what the user sees to, well, play the animation. It works in the same way you are used to from common video players.

![H5P.Animator player overview](assets/animator_player_overview.png?raw=true)

1) __Animation:__ Here's the animation, which can consist of several elements, as in this example: a background image (lake in Tromsø, Norway), text ("Shapes, too ..."), a red square, a green circle, and a blue rectangle.

2) __Player controls:__ Here the user can play/pause the video, search, and toggle fullscreen mode on and off.

## Player controls
![H5P.Animator player controls](assets/animator_player_controls.png?raw=true)

1) __Play/Pause Button:__ This button allows the user to play and pause the animation. Note that this button is temporarily disabled if you use background audio. The browser has to buffer the audio file first. Pressing the `k` key will also play/pause the animation.

2) __Slider:__ This slider allows the user to move back and forth in the animation. You can also use the `j` key to go back one second and the `l` key to go forward one second.

3) __Time display:__ The time display shows the elapsed time and the total time of the animation in common time code notation.

4) __Fullscreen Button:__ This button allows the user to switch to fullscreen mode. Note that this button is not available if the content cannot be sent to full screen in the current context.

## Additional notes
While the player has focus, which it usually does after you click on it, you can use the `k` key to play/pause, the `j` key to go back one second, and the `l` key to go forward one second.
