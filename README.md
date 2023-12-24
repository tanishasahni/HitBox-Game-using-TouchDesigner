# HitBox-Game-using-TouchDesigner
A game created in TouchDesigner that uses hand tracking to move a hitbox in attempt to catch the moving circle.

Hand tracking plugin is from [torinmb/mediapipe-touchdesigner](https://github.com/torinmb/mediapipe-touchdesigner).

<img width="1512" alt="Screenshot 2023-12-23 at 9 39 00 PM" src="https://github.com/tanishasahni/HitBox-Game-using-TouchDesigner/assets/148817753/9eec2674-1a44-4786-82b1-b39f37af14f4">

# Objective
Use your hand to control the hitbox in attempt to touch the moving red circle. Timing and precision are crucial to successfully aim for the target.

# Gameplay
There are three rounds to the game, each slightly difficult than the previous one. When the player successfully aligns the hitbox with the circle, the next round will start after "WINNER" is briefly displayed. After the player completes all three rounds, the game will reset and start from round one again.

# Additional Notes
To reset the camera detection, simply move your hand out of the frame. You can continue moving the box once your hand is in frame again. 
