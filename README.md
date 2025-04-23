This project demonstrates real-time object tracking with motion and color detection using OpenCV and Python. The application captures video from a webcam, processes each frame to detect and track objects based on predefined color ranges (in HSV color space), and highlights them with bounding circles and color labels. The processed video is saved for further analysis.

**Key Features:**
- Real-Time Object Detection: Detects objects based on their color in real-time, using predefined HSV color ranges.
- Motion Tracking: Continuously tracks the movement of the detected objects in each frame.
- Color Classification: The system identifies and labels detected objects with their respective colors (e.g., Red, Green, Blue, Yellow, White, Black).
- Multi-object tracking: The system tracks multiple objects of different colors simultaneously.
- Efficient Processing: The code uses contour detection and circularity checks to filter out noise and improve tracking accuracy.
- Customizable Color Detection: Easily add or modify color ranges to track different objects based on their color.
- Video Output: The processed video is saved as color_ball_tracking.mp4 and can be viewed to observe the tracking in action.

**How It Works:**
1. Capture Video: The webcam captures real-time video frames.
2. Convert to HSV: Each frame is converted to HSV color space for better color detection.
3. Apply Color Masks: Predefined color ranges are applied to detect objects of specific colors.
4. Contour Detection: Contours of detected objects are identified and analyzed.
5. Track Objects: The center and radius of each detected object are calculated and displayed on the frame.
6. Display and Save: The video is displayed frame-by-frame, and the output is saved.

**Output:**
The program processes video in real-time, detecting objects in various colors, and tracks their movement. The resulting video is saved as an mp4 file.
