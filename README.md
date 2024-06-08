# EyeGazeNavigator

This Python script uses OpenCV and PyAutoGUI to create an eye-tracking system that controls the mouse cursor. The script captures video input from a webcam and detects faces and eyes using Haar Cascades. Eye positions are translated into screen coordinates to move the cursor smoothly. It also detects blinks to simulate mouse clicks. The system includes smoothing to ensure stable cursor movement and prevents accidental clicks by setting a blink threshold.
