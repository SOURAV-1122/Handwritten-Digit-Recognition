# digit-recognizer

Web demo to recognize handwritten digits using your phone or a webcam.

For best results:

  1. Write 1 digit at a time, alone with a thick marker, about 1" or bigger to get a good image
  1. Write on a light background in a dark color
  1. Use clear bright lighting
  1. When positioning your camera, center your digit in the yellow box on screen
  1. Write numbers in your own style - it was trained to work with different handwriting styles

## Features / notes

The whole thing is running on your device - there's no backend.

Uses WebRTC to connect to the camera and take a snapshot every .5 seconds. Then grabs a square of image with getImageData(). Then parses that into a black and white image. Then feeds those 28*28 pixels into the neural network.

Has an autocenter feature which recenters the black pixels in the middle of the image. You can see this working in the processed image preview in the upper-left.

## Troubleshooting

If the camera doesn't work, refresh and give permissions to use the camera. If that doesn't work, go into your device's settings to give your browser app permission to use the camera.


## Additional Features / Notes
Cross-Platform Compatibility: Works on both desktop and mobile browsers, ensuring a wide range of device support.

Real-Time Prediction: Instant feedback on the digit drawn, providing a seamless user experience.

Customizable Styles: Users can adjust the size and color of the drawing area for better visibility.

Learning Mode: An interactive tutorial mode that guides users through the process of writing digits and understanding predictions

Data Privacy: Processes images locally, ensuring user data is never sent to external servers.
## Usage Instructions
Browser Compatibility: Recommended to use modern browsers (Chrome, Firefox) for the best performance.

Camera Permissions: Ensure that your browser has camera access enabled; this is critical for the application to function.
## For Any Queries
Contact the Developer: For additional questions or support, feel free to reach out via souravoffice8499@gmail.com
