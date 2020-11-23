 ## **[FilterFun](https://mariagamal.github.io/FilterFun/)**

An interactive webpage where you can upload your images and adds filters to them.

## **Table of contents**
- General info
- Techologies
- Demo
- Code Description
- Status

## **General info**:

This is the final project of the course, Programming Foundations with JavaScript, HTML and CSS, Offered by Duke University through Coursera. It displays a webpage, made by codepen.io, where a user can upload and display images, apply filters to them and reset images to their orignal versions. 

## **Technologies**:
- HTML
- CSS
- Javascript

## **Demo**

Down below is an image from Unsplash that used to test. Obviously, it has many colors that's why it was preferred to test all filters.

![IMG](https://source.unsplash.com/IGfIGP5ONV0)

### List of Filters

1. Original

![Original](https://i.ibb.co/KxtBZtt/screencapture-mariagamal-github-io-Filter-Fun-2020-11-21-01-24-51.png)

2. GrayScale

![GrayScale](https://i.ibb.co/pWYM67k/GS.png)

3. Red Tone

![Red](https://i.ibb.co/Kmy1yH1/RED.png)

4. Rainbow Colors

![Rainbow](https://i.ibb.co/hxzjWxM/RNB.png)

5. Blur Effect

![Blur](https://i.ibb.co/vz42tQW/Annotation-2020-11-21-015112.pngv)

### **Give a Try!**

You can try your images and add filters to them using this link:

[FilterFun](https://mariagamal.github.io/FilterFun/)

## **Code Description:**
The code is composed of about 7 buttons. Each button is associated with a javascript function listed below:

 > "Choose Files" : Allows you to upload your image in the canvas. The image is displayed with its original dimensions.

 > "makeGrayScale" : Sets the RGB values of all pixels to the average of the current values.

 > "makeRed" : Based on the average of the RGB values of the pixels, the function does some calculations to add a red filter to the image.

> "ResetImage" : Removes all filters and displays the original image through the use of global variables.

>"ClearCanvas" : Empties the canvas.

> "makeRainbow" : Using the RGB values of the rainbow's seven colors, this function divides the image into 7 stripes, each using the RGB values of one of these colors.

> "makeBlue" : This filter is achieved by generating random numbers and based on these numbers, either the original pixel is displayed in the same pixel location or a nearby pixel is displayed in the pixel location.


## **Status**
Project is in progress.




