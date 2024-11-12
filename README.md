#  Ex 9 - Implementation of Erosion and Dilation
## Aim
To implement Erosion and Dilation using Python and OpenCV.
## Software Required
1. Anaconda - Python 3.7
2. OpenCV
## Algorithm:
### Step 1:
Import the required libraries.
### Step 2: 
Create a text image using cv2.putText().
### Step 3: 
Define a structuring element for the erosion and dilation operations.
### Step 4: 
Apply erosion to the image using cv2.erode().
### Step 5: 
Apply dilation to the image using cv2.dilate().
### Step 6: 
Display the original, eroded, and dilated images.
 
## Program:
```py
### Developed by : PAVITHRA R
### Reg.no : 212222230106
```
```
import cv2
import matplotlib.pyplot as plt

# Display the image using matplotlib
plt.figure(figsize=(10, 5))

# Convert BGR (OpenCV format) to RGB (matplotlib format)
image_rgb = cv2.cvtColor(image, cv2.COLOR_BGR2RGB)
eroded_image_rgb = cv2.cvtColor(eroded_image, cv2.COLOR_BGR2RGB)
dilated_image_rgb = cv2.cvtColor(dilated_image, cv2.COLOR_BGR2RGB)

# Plot images
plt.subplot(1, 3, 1)
plt.imshow(image_rgb)
plt.title('Input Image')

plt.subplot(1, 3, 2)
plt.imshow(eroded_image_rgb)
plt.title('Eroded Image')

plt.subplot(1, 3, 3)
plt.imshow(dilated_image_rgb)
plt.title('Dilated Image')

plt.show()

```
## Output:

### Display the input Image:


![image](https://github.com/user-attachments/assets/6241ddcd-11f4-4c10-99e4-092ad4abb3f7)

### Display the Eroded Image:


![image](https://github.com/user-attachments/assets/782fd875-2855-4215-b43e-5fc8887e075b)


### Display the Dilated Image:


![image](https://github.com/user-attachments/assets/129a2d1d-4475-4baf-8e72-5986dd0671d0)


## Result
Thus the generated text image is eroded and dilated using python and OpenCV.
