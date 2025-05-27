# image-blending-trackbar-opencv
This Opencv project allows you to blend two images using trackbar. A switch is provided to toggle the blending ON or OFF. When OFF, a blank image is shown.
## Features
- Blend two images in real-time using a trackbar(1-100)
- Switch (via trackbar) to toggle between blended output and a blank image
- Smooth and dynamic transition between images
## How It Works
- The trackbar controls the blending factor 'alpha' (0.0 to 1.0)
- The two images are blended using Opencv's 'cv2.addWeighted()' method
- A switch trackbar enables or disables the output:
- switch = 0 -> blank image
- switch = 1 -> blended output 
