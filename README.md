# SiaAppChallenge2018
the SIA application we created consist of two parts to the code. The one on the device, and the Kivy application.
link to the video can be found:[here](https://www.youtube.com/watch?v=4jCmanZKkEM)

## Kivy App
The application is meant to be accessed from the warehouse. </br >The main file will be the SIAUI.py.
Application will be accessed from the warehouse at the airport. </br >
They will be able to recieve information about the quantity required once the plane lands, and do the preperation of the stock accordingly</br >
By calling SIA API, we are able to get quantity of supply at warehouse.</br >

<img src="https://github.com/HoJinKind/SiaAppChallenge2018/blob/master/images/Screenshot%20(85).png" alt="alt text" width="415" >  <img src="https://github.com/HoJinKind/SiaAppChallenge2018/blob/master/images/Screenshot%20(86).png" width="425"/> 
</br>For fully stocked preflight recordings.</br>
<img src="https://github.com/HoJinKind/SiaAppChallenge2018/blob/master/images/Screenshot%20(87).png" width="425"/> 
</br>Example of updated supply after flight.</br>

## Rpi/hardware
A modular device which is small and easily detachable. </br >Powered by portable batteries, it uses sensors to determine the quantity of plates at that instant, and update Firebase.
