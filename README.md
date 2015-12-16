# Location Notification
Location Notification is an android application that automates your phone's notification settings. It periodically checks your location and adjusts your phone's notification setting to the requested setting (Normal, Vibrate, Silent).

##Main Activity
This is what opens when you first launch the app. It gives you a switch to enable/disable the app and a floating action button to add a preset. Given that this app is built with android Marshmallow's permission system in mind, it will ask you to accept the permissions it needs to run smoothly.

![Main Screen](https://github.com/OmarAlmootassem/Images/blob/master/LocationNotification2.png?raw=true)

##Add Preset Activity
This activity is launched when the floating action button in the previous activity is pressed. In this activity, you add a preset by choosing the location, notification setting, and the place nickname. When you are done, you save it using the save button in the action bar. It uses Google Maps API to display the map and it uses Google Places API for the autocomplete place search box.

![Add Preset Screen](https://github.com/OmarAlmootassem/Images/blob/master/LocationNotification3.png?raw=true)

##Main Activity
After adding a preset or 2, the Main Activity will update and display cards with information about the presets including location name, static map image and sound profile for that location. The static map images are generated using Google Static Maps API.

![Main Screen](https://github.com/OmarAlmootassem/Images/blob/master/LocationNotification1.png?raw=true)
