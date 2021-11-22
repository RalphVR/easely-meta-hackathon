# easely-meta-hackathon

## Instructions
1. download apk and sideload unto Quest 2 (have not tested on Quest 1)
2. start the app, ensure microphone permissions accepted for voice commands to work properly
3. select from built in library of images or enter the email associated iwht your flickr account to download your public flickr photos
4. grab the selected image using the grip button on the controller and place controller top of ring flush against the drawing surface you will use
5. release image. use thumbstick to adjust size and opacity
6. reduce opacity of image enough to see your drawing underneath
7. use voice commands ot change opacity, image style, and a few other commands

## Known Issues
* The framerate hitches when the image database is loaded. It also hitches when applying an image effect. These are known and we just ran out of time to convert the code to use asynchronous methods.
* We are using flickr :P I mean, flickr is great, but most folks don't really use it. Most image databases use OAuth2, which we don't believe works on Quest yet. Flickr has a very easy API and is simple to create some public images for. We will support more databases in the future, as well as allow custome folders 'n' such on flickr and elsewhere.
* The hide controls voice command hides the voice controls panel, not the controls panel.
* The passthrough mode image warps and can cause challenges when drawing. Eh, this is a prototype and we expect the app to grow in both features and functionality as the technology and headsets for AR, MR, and passthrough continue to mature. We think Passthrough is super cool and believe the app is pretty cool even as a prototype.

## Plans for the future
We have so many ideas for this app! Once we get some rest after the past few days of pulling the demo together we will update this readme with some thoughts for the future.
