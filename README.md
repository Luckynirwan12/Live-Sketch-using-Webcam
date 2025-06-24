# Live-Sketch-using-Webcam
## 📌 Description
This is a fun and simple computer vision project using OpenCV that captures real-time video from your webcam and converts each frame into a pencil sketch effect. It mimics how an artist might draw an image using only lines and shading — making it look like a hand-drawn sketch!

## 🔧 Technologies Used
- Python 3.x

- OpenCV (`cv2`)

- NumPy

 ## 🎯 Features
- Captures live video using your webcam.

- Applies real-time sketch effect using:

    - Grayscale conversion

    - Gaussian Blur (noise reduction)

    - Canny Edge Detection

    - Binary Inverted Thresholding

- Displays the result in a live OpenCV window.

- Press Enter to exit the sketch window safely.

 ## 🚀 How It Works
1. Captures each frame from the webcam.

2. Converts it into grayscale for simplicity.

3. Applies Gaussian Blur to reduce noise.

4. Detects edges using the Canny algorithm.

5. Applies binary inversion thresholding to highlight lines.

6. Continuously displays the "sketched" frame in a window.

 ##  🛠️ Steps to Run 
1. First, I saved the Python file (`Live_Sketch_Using_Webcam.ipynb`) to my Desktop.

2. Then, I opened the Anaconda PowerShell Prompt and typed the following:
   - `cd Desktop`
  
   - `jupyter notebook`


3. This opened the Jupyter Notebook interface in my browser.

4. I selected the file named `Live_Sketch_Using_Webcam.ipynb` from the list.

5. I ran the code cell-by-cell using Shift + Enter.

6. The webcam window appeared, and it started showing the sketch effect in real-time.

7. To exit, I pressed the Enter key in the webcam window.
