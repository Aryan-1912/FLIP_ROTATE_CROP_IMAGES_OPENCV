# FLIP_ROTATE_CROP_IMAGES_OPENCV
Here i have done 3 operations on a single images. operations such as flipping, rotating, cropping images using OpenCV


📂 FLIP_ROTATE_CROP_IMAGES_OPENCV
🎯 Objective
This project demonstrates how to perform fundamental image transformation techniques — flip, rotate, and crop — using OpenCV in Python. These operations are commonly used in image preprocessing, data augmentation, and computer vision pipelines.

🛠️ Technologies Used
🐍 Python

📸 OpenCV (cv2)

🧪 Jupyter Notebook (.ipynb)

✨ Features
✅ Flip images horizontally, vertically, or both using cv2.flip()

✅ Rotate images using both fixed angles (cv2.rotate) and custom angles via rotation matrices

✅ Crop images using slicing and coordinate logic

✅ Cleanly visualized results using matplotlib.pyplot

📁 File Structure
bash
Copy
Edit
📦 FLIP_ROTATE_CROP_IMAGES_OPENCV/
 └── Flip_crop_rotate_img.ipynb   # Main notebook demonstrating all operations
🧪 Sample Code Snippets
🔄 Flip
python
Copy
Edit
flipped_h = cv2.flip(image, 1)  # Horizontal
flipped_v = cv2.flip(image, 0)  # Vertical
🔃 Rotate
python
Copy
Edit
rotated = cv2.rotate(image, cv2.ROTATE_90_CLOCKWISE)
✂️ Crop
python
Copy
Edit
cropped = image[50:200, 100:250]  # Crop region from y=50–200 and x=100–250
📸 Output Example
The notebook displays:

Original image

Horizontally and vertically flipped images

Rotated versions (90°, 180°, 270°)

Cropped regions of interest

📌 Usage
Clone the repo:

bash
Copy
Edit
git clone https://github.com/Aryan-1912/FLIP_ROTATE_CROP_IMAGES_OPENCV.git
Open the Jupyter notebook:

bash
Copy
Edit
jupyter notebook Flip_crop_rotate_img.ipynb
Run each cell and view transformation results.

🙋‍♂️ Author
Aryan Prajapati
📫 LinkedIn
🔗 GitHub: Aryan-1912
