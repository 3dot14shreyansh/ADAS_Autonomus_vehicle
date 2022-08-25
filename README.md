# ADAS_Autonomus_vehicle

### 3-channel image to Grey-scale conversion:
- Image is generally three channeled coluored pixel that is [Red, Blue, Green] which ranges from [0, 0, 0]-white and [255, 255, 255]-black.
- The grey-scale is one channnel coloured pixel which ranges from 0 to 55. Where 0 is white and 55 is black.
- Computaionally is difficult to process 3-channel coloured pixel when compared to grey-scale.
- Therefore we will first convert image to grey-scale
```python

grey_image = cv2.cvtColor(lane_image, cv2.COLOR_RGBGRAY)
cv2.imshow('result'. grey_image)
```
![alt text](http://url/to/img.png)
![alt text](http://url/to/img.png)
