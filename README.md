Android Utility
======

Utility library for common and daily used android methods

Simple easy to use methods to save time on developers, no need to write basic and common methods every time in every project.


Methods
-----
The project contain five basic classes:
* ActivityAnimation: Basic methods for transaction between activities 
* HttpUtility: Common methods for Http connection 
* ImageUtility: Methods to manipulate and edit images as needed e.g. convert bitmap to circle, rounded corner or gray image and more methods
* LogManager: Control your logs in one place so you can turn off debug on release with just one line of code
* Utility: general utilities for android development e.g. check network, check if screen portrait or landscape, is app in foreground and more

Setup
-----
Import the project “Android Utilities” and add it in build path after import it (in Eclipse: right click on your project > Properties > Android > Add..)

OR add the “utility.jar” in lib folder in your project

Example
-----
- Image Utility 
``` Bitmap cutome = ImageUtility.getCircleBitmap(bitmap); ```
![alt tag](https://raw.github.com/Barqawiz/AndroidUtility/master/example/circle_image.png)

``` Bitmap cutome = ImageUtility.rotateBitmap(bitmap, 30); ```
![alt tag](https://raw.github.com/Barqawiz/AndroidUtility/master/example/rotate_image.png)


- Utility
``` ProgressDialog loading = Utility.createLoadingDialog(this); ```
![alt tag](https://raw.github.com/Barqawiz/AndroidUtility/master/example/loading_view.png)


Developed By
------------

Ahmad Barqaiw
@Barqawi88


License
-------
  GNU GENERAL PUBLIC LICENSE
