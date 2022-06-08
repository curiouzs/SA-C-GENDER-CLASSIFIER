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

#import libraries

from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt

#read the image
img=cv2.imread('GowriM.jpeg')
plt.imshow(img[:,:,::-1])
plt.show()

#To identify the gender
result=DeepFace.analyze(img,actions=['gender'])
result2=DeepFace.analyze(img,actions=['emotion'])
print("Gender : ",result['gender'])

```

## OUTPUT:

1. CODE :
![SKILL ASSESSMENT OUTPUT](XXX.png)

2. DEMO VIDEO YOUTUBE LINK:


