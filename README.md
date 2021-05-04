ITCS 4152/5152 Computer Vision    Spring 2021

Group Name: Visionaries

Group Members:  Hari Chamlagai, Cade Mack, Amanda Cheng, AJ Daodu, Haroon Kaid, Aryani Patel
                       
The Idea: Dash Cam License Plate Detection

There are many variations and uses of license plate readers such as those used at traffic lights and those used in parking decks for vehicle identification. The common trait between most license plate readers is the environment they are designed to be used in. Both traffic light and parking deck readers will house cameras high up and exclusively feed data into a model from an angle looking down. In the Traffic Lights case the subject is always moving relative to the stationary camera and in the parking decks case, the subject is stationary relative to a still camera.

As with the genesis of many interesting ideas; we start by identifying a dearth in a niche market. Through our research we found little to no models license plate detection focused on a view from a dash cam. The number of people with dash cams is growing and with that so does the need to efficiently identify information from those cameras.

Our group has focused on creating and training a model best for the angle commonly found in vehicle dash cams. In dash cam license plate detection, unlike other uses, both the subject and the camera are in motion. This is represented both in the model we have created and the data we have used to train that model. The data consists of head on shots of license plates common in dash cams and many instances where the subject and camera are both in motion.

[image](https://user-images.githubusercontent.com/54340064/116956220-b21dc500-ac62-11eb-960a-e636a8a850bb.png)
