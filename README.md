In this project, we created a real-life "Invisibility Cloak" using computer vision techniques, leveraging Python, OpenCV, and NumPy libraries. 
Inspired by fictional concepts, the aim was to make objects or people appear invisible in a video feed, simulating the effect of an invisibility cloak.

Key Features:
Background Subtraction: The core concept revolves around detecting a specific color (in this case, the color of the cloak) and replacing it with the background. This makes the cloak appear invisible.

Real-time Video Processing: Using OpenCV, the script captures live video from a camera, processes each frame in real-time, and applies the invisibility effect dynamically.

Color Detection and Masking: A specific color range (e.g., red or blue) is defined, and pixels matching this range are masked. 
NumPy arrays are used to efficiently manipulate image data and handle pixel-level operations.

Python Scripting: Python scripts were used to integrate all components—capturing video input, applying the color detection mask, and rendering the final output with the invisibility effect.

Technologies and Libraries:
OpenCV: For video capture, color detection, and real-time frame manipulation.
NumPy: For handling image arrays and performing efficient numerical operations.
Python: The backbone of the project, used for writing scripts and implementing logic.

This project demonstrated how basic principles of computer vision could be applied to create engaging and interactive effects like an "Invisibility Cloak," blending both fun and learning in image processing and real-time video manipulation.
