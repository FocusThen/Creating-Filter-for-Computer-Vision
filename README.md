# Creating-Filter for Computer Vision
### Sobel

![ss2](https://user-images.githubusercontent.com/47830409/63850261-56366f80-c99c-11e9-84f0-af2db44b9ca8.PNG)

### Sobel Filter

```sh
#Sobel filter
sobel_x = np.array([[-1,0,1],
          [-2,0,2],
          [-1,0,1]])
filter_image = cv2.filter2D(gray_image, -1, sobel_x)
```
![ss1](https://user-images.githubusercontent.com/47830409/63850236-47e85380-c99c-11e9-8305-b2d0a5d42564.PNG)
