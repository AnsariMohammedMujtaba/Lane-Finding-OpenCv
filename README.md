# Lane Detection Using OpenCV

This project implements a lane detection system using OpenCV in Python. The system processes video frames to detect and highlight lanes on the road, utilizing various image processing techniques.

## Technique Used

- **Canny Edge Detection:** Converts the frame to grayscale, applies Gaussian blur, and detects edges using the Canny method.
- **Region of Interest (ROI):** Focuses the lane detection on a specific region of the frame where lanes are expected to be.
- **Hough Line Transform:** Detects lines in the ROI using the Hough Line Transform.
- **Averaging Lines:** Averages multiple line segments to create a single line for each lane.
- **Overlay Lines:** Draws the detected lanes onto the original frame.

