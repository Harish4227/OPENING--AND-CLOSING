# EXP-10-OPENING--AND-CLOSING
### Name - Harish D
### Register Number - 212224220034
## Aim
To implement Opening and Closing using Python and OpenCV.

## Software Required
1. Anaconda - Python 3.7
2. OpenCV
## Algorithm:
### Step1:
Import the necessary packages


### Step2:
Create the Text using cv2.putText

### Step3:
Create the structuring element

### Step4:
Use Opening operation

### Step5:
Use Closing Operation
## Program:

``` Python
# Import the necessary packages
import cv2
import numpy as np
import matplotlib.pyplot as plt

# Create a blank image

# Create the Text using cv2.putText



# Create the structuring element

# Add text on the image using cv2.putText
font = cv2.FONT_HERSHEY_SIMPLEX
cv2.putText(image, 'Open and Close', (100, 250), font, 1, (255, 255, 255), 2, cv2.LINE_AA)

# Use Opening operation


# Create a simple square kernel (3x3)
kernel = np.ones((3, 3), np.uint8)
# Display the input image
plt.imshow(cv2.cvtColor(image, cv2.COLOR_BGR2RGB))  # Convert BGR to RGB for displaying
plt.title("Input Image with Text")
plt.axis('off')

# Use Closing Operation

# Display the result of Opening
plt.imshow(cv2.cvtColor(opened_image, cv2.COLOR_BGR2RGB))  # Convert BGR to RGB
plt.title("Opening Operation")
plt.axis('off')



```
## Output:

### Display the input Image
<br>
<br>
<br>
<br><img width="297" height="962" alt="image" src="https://github.com/user-attachments/assets/79163aff-d430-45e7-82a0-2feeccfa840d" />

<br>
<br>

### Display the result of Opening
<br>
<br><img width="706" height="488" alt="image" src="https://github.com/user-attachments/assets/17756d0c-d24d-4b0c-8403-b5939ba77922" />

<br>
<br>
<br>
<br>

### Display the result of Closing
<br><img width="831" height="502" alt="image" src="https://github.com/user-attachments/assets/79a58dad-941f-4cf3-8192-9daf3b5e877e" />

<br>
<br>
<br>
<br>
<br>

## Result
Thus the Opening and Closing operation is used in the image using python and OpenCV.
