# Clima

This is a weather app that enables users to check real-time weather information.
Upon opening the app, it requests permission to use location data. Simultaneously, it fetches location data based on the user's latitude and longitude.
If users input the desired city name in the text field, press Enter, or click the magnifier button, real-time weather information for that city is updated.
The app supports both default and dark mode, with icons and wallpapers adapting to the chosen mode.
To design the code efficiently, the Delegate design pattern is employed for increased efficiency. Additionally, protocols and extensions are utilized to support the viewController. The code is simplified using closures, taking advantage of the anonymous feature.
Real-time weather information is updated through the Open Weather API, and networking is established using URL sessions.
The JSON format is employed for decoding and utilizing real-time weather information, with computed properties optimizing its efficient use.
Error handling is appropriately implemented, and the Core Location function reflects the user's real-time location.
Furthermore, plists are added to manage Core Location manager in a pop-up message.



https://github.com/dlwngh1367/Clima/assets/107776511/f43c8e5d-ae70-4a04-a4c1-6b7b9e81add6

