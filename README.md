# Clima

This is a weather app that allows users to check real-time weather information.
Once users open the app, it will ask users for permission to use location data.
At the same time, it will fetch the location data base on user's latitude and longitude.
If users enter the name of the city they want in the text field, press Enter or click the magnifier button, real-time weather information for that city will be updated.
This app supports both default and dark mode, and depending on the mode, the icon and wallpaper change to suit the situation.
To design the code efficiently, Delegate design patterns were used to increase efficiency, and to support this, I used the protocol, the extension, to repactor the viewcontroller.
In addition, I was able to write the code more simply using the anonymous feature which is Closure.
I updated real-time weather information using open weather API and connected using URL session for networking.
The JavaScript Object Notation (JSON) format was used, real-time weather information was decoded and used, and Computed properties were utilized to use real-time information more efficiently.
The error was properly handled and the Core Location function was used to reflect the real-time location of the user.
Moreover, I added plists to handle Core Location manager in a pop-up message.



https://github.com/dlwngh1367/Clima/assets/107776511/97fe7ff7-057b-4347-b7e1-14377b358aa6

