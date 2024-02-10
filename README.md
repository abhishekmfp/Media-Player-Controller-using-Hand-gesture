# Media-Player-Controller-using-Hand-gesture
In this Project we control our media player using hand gestures with the help of OpenCV and Python.

The purpose of the gesture control media player project is to develop 
a system that allows users to control media playback functions using 
hand gestures. By leveraging computer vision techniques and the 
OpenCV library, the project enables users to interact with the media 
player interface in a more intuitive and hands-free manne

# Steps of project implementation
  1. Import Libraries and capture camera
  2. Convert frames into hsv
  3. Track hand on color basis
  4. Create mask on the basis of color and filter actual color
  5. Invert pixel value and then enhance the result for better output
  6. Find contours for specific object
  7. Find max area contour and draw it on live feed
  8. Find convexity defect for counting values and apply cosin method
  9. Bind Hand gestres with keyboard keys
  10. See the result
