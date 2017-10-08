# YouTube Remote Zero
Control YouTube running in your desktop browser from your Android phone. 

<img src="screenshot.png" width="256px">

## requires
receiver_zero (https://github.com/matdombrock/receiver_zero)

This Android app communicates with your computer via the 'receiver zero' desktop application. 

'receiver_zero' must be running in order for 'YouTube Remote Zero' to work.

## usage
When you launch 'receiver_zero' on your desktop, you will see a console window open up with a line which will look something like:
```
Server Running on Local IP: 10.0.0.6
```
Copy this IP into the 'YouTube Remote Zero' app on your phone. 

The port should be set to '3333' by default, leave that how it is because that's the default port for the 'receiver_zero' server. 

Make sure that you have a browser window open with a YouTube video ready to go. You should open a video page that looks something like this:

https://youtu.be/G2_Q9FoD-oQ

Once you have a video ready to play (or playing) you can sit back and enjoy using the remote. 

*It is also possible to use the 'open' button inside the app to go to a page (any page) as long as you at least have your browser open and focused (it was the last window you clicked on). You can use this to open YouTube if it isn't already open, or to go to a specific video that is not in your current playlist.*

**Note that this app will only work if your phone is on the same wifi/lan as your computer. It is possible to get around this with port forwarding but I would strongly discourage that for security reasons.**

## todo
-Allow sharing of video links from the YouTube app directly into 'YouTube Remote Zero' so that it is possible to open new videos or playlists without manually copying the URL. 

-Fix layout for all screen sizes (I don't understand constraints very well).