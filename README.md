# ArDrone
Tutorial to use a Parrot ArDrone 2.0 with Pharo and LRP. You need a basic level about Pharo to undestand this instructions.

### Initialization
To start using the Parrot ArDrone 2.0 with Pharo and LRP, you need to download a clean image from [download](https://pharo.org/web/download) page of Pharo.

### Installation
* After download the image of Pharo, you need to install the LRP in your image, do-it of the following in a playground window:

  ```pharo
  Gofer it
    smalltalkhubUser: 'jfabry' project: 'LiveRobotProgramming';
    configuration;
    loadDevelopment
  ```
* Now, with LRP installed, you have to download the ArDrone API to Pharo. The source can be merged to the current image using monticello browser, the package is allowed in this link from smalltalkhub: [http://smalltalkhub.com/#!/~CaroHernandez/ArDronePharo](http://smalltalkhub.com/#!/~CaroHernandez/ArDronePharo). If you don't know how download code from smalltalkhub or use monticello browser, you can read the chapter 8 from the book [Pharo by Examples](http://files.pharo.org/books/updated-pharo-by-example/). The following image, show the code that you need to load in your image: 

![monticello browser Drone-API](/img/PharoAPIDroneInstallation.png)

  Remember load *ONLY* the ArDrone package!. 

* After loaded the API, you must load the Bridge to conect the LRP with the ArDrone API. The code is in smalltalkhub, again you have to load with monticello browser this link: [http://smalltalkhub.com/#!/~CaroHernandez/LiveRobotics-ARDrone](http://smalltalkhub.com/#!/~CaroHernandez/LiveRobotics-ARDrone). And agein you have to load the last, how shows the image: 

![monticello browser bridge](/img/PharoBridgeLRP-ArDrone.png)

* Now you have installed the Ardrone API, the LRP and the Bridge between them so if you make a left click in the world of pharo, you will see the following:

![lrp in pharo world menu](/img/PharoWorldMenu.png)

And that is all!, now you can flight your ArDrone 2.0 with Pharo and LRP, create and modify state machines for the drone. In this [github]() you can download some examples. 

*Important:* The video is not implemented in this tutorial so you will not see the drone camera , we are working to implemented!
