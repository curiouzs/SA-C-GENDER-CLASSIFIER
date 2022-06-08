# SA-C-GENDER-CLASSIFIER
# Algorithm
1.Install deepface

2.Import necessary packages

3.Read the image

4.Analyze the gender using deepface

## Program:
```python
"""
Program to implement Gender Classification
Developed by   : Lokesh Krishnaa M
RegisterNumber :  212220230030
"""
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
#1st image
img=cv2.imread('tata.jpg')
plt.imshow(img[:,:,::-1])
plt.show()

result=DeepFace.analyze(img,actions=['gender'])
print("Gender : ",result['gender'])

#2nd image
img1=cv2.imread('bobby.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()

result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])

#3rd image
img2=cv2.imread('modi.jpg')
plt.imshow(img2[:,:,::-1])
plt.show()

result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])

```

## OUTPUT:

1. CODE :

![sa1](https://user-images.githubusercontent.com/75234646/172662768-39c9b626-071d-4761-a65b-64b287f483f8.PNG)

![sa2](https://user-images.githubusercontent.com/75234646/172662776-e7fd292f-34ac-4318-b254-32641cb69203.PNG)

![sa3](https://user-images.githubusercontent.com/75234646/172662788-6363d980-b941-472b-b9d3-27cddfd142b4.PNG)

2. DEMO VIDEO YOUTUBE LINK:


