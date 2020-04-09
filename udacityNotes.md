How **android** works??

![C:\\Users\\Home\\Desktop\\Capture.PNG](media/image1.png){width="6.268055555555556in"
height="3.1605129046369203in"}

**Appcompat** class has the **findViewById** method.

When the app is compiled, **aapt** generates **R** class which contains
the **id** s of all the items in the **resource folder.**

![](media/image2.png){width="6.268055555555556in"
height="3.472916666666667in"}

**Padding vs margin**

![C:\\Users\\Home\\Desktop\\Capture.PNG](media/image3.png){width="6.268055555555556in"
height="3.309257436570429in"}

**How to start designing??**

![](media/image4.png){width="6.268055555555556in"
height="3.379166666666667in"}

**Adding an image in the drawable folder**

![C:\\Users\\Home\\Desktop\\Capture.PNG](media/image5.png){width="6.268055555555556in"
height="4.100263560804899in"}

**Changing the size of the image??**

We have **scale Type** for that,

There are many possible values for the scale type, we ll see on the
basic two types:

**CENTER:** Center the image in the view, but perform no scaling.

**CENTER\_CROP:**

According to documentation it says...Scale the image uniformly (maintain
the image\'s aspect ratio) so that both dimensions (width and height) of
the image will be equal to or larger than the corresponding dimension of
the view (minus padding). The image is then centered in the view.

![C:\\Users\\Home\\Desktop\\Capture.PNG](media/image6.png){width="5.741666666666666in"
height="4.825in"}

To be simple cross crop expands the image equal to the size of image
view and then crops the left over In order to make uniform change in
height and width.

**Note:When an integer is concatenated with a string it also becomes a
string.**
