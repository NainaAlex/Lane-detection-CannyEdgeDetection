# Lane Detection using Canny Edge
A basic project that demonstrates how Canny Edge Detection can be used to find straight lines in an image or video, as in this case.
The images below are just 1 frame from the video
## Original Image
<img width="923" alt="Capture_orig" src="https://user-images.githubusercontent.com/67065986/111970872-c7f78080-8b21-11eb-948d-46ec37e9edc8.PNG">

## GrayScaled Image
<img width="959" alt="Capture_grayscale" src="https://user-images.githubusercontent.com/67065986/111970963-df366e00-8b21-11eb-9494-dabe1e9df9cc.PNG">

## Canny Edge Filter
<img width="960" alt="Capture_canny orig" src="https://user-images.githubusercontent.com/67065986/111972986-0a21c180-8b24-11eb-9a24-b293c54aaa52.PNG">

## The Polygon
The points I have specified here are the dimensions of the polygon.
<img width="960" alt="Capture_canny" src="https://user-images.githubusercontent.com/67065986/111972762-d0e95180-8b23-11eb-8eb2-86fa7952382e.PNG">


Now that we know the region that we want to detect our lanes.
We can use Hough Lines function which finds all the points in the image, and using that data, it finds the lines that satisfy the most number of points.
Those lines can then be drawn in each frame and so it is able to display the outlines of the lanes.
