# Hand Gesture Media Player
This project features a music website in which the playback can be controlled using Hand Gestures. This is achieved by making use of the SSD MobileNet architecture which was trained on a dataset comprising of 4,000 hand gesture images, including Fist, Palm, Point, and Pinch gestures. This was done by Victor Dibia (https://github.com/victordibia/handtracking). This pre-trained model was used to map the different functions in a music player to different gestures. 

The current mappings are -
✊Fist - Play/Pause 
🖐Palm - Next 
👆Point - Previous
🤏Pinch - Volume

This model is very easy and convenient to use. This is especially useful for specially-abled people. It can work even while the window is minimized, making it possible to control the playback without any clicks. Although it takes up a lot of resources to run, it is reliable. In the future, I would like to map more gestures to functions, make it less computationally expensive and integrate an API with which a user make choose their own songs.
