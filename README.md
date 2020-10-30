# AndroidRTCCaller

The original version is here: [AndroidRTC](https://github.com/pchab/AndroidRTC)



## WebRTC Live Streaming

An Android client for [ProjectRTC](https://github.com/pchab/ProjectRTC).

It is designed to demonstrate WebRTC video calls between androids and/or desktop browsers, but WebRtcClient could be used in other scenarios. 
Build with Android Studio 1.1.0. The Intellij IDEA version is in the master branch.
You can import the webrtc-client module in your own app if you want to work with it.

It is also featured in the [Android Arsenal](https://android-arsenal.com/details/3/1262) !

## How To

You need [ProjectRTC](https://github.com/pchab/ProjectRTC) up and running, and it must be somewhere that your android can access. (You can quickly test this with your android browser). Modify the host string (in res/values/strings.xml) to the server IP.

When you start the app you'll find an input text and a call button: insert the remoteID in the input text and the press the call button. You should start seeing what the remote is streaming.

Used in combo with [ScreenShareRTCAndroid](https://github.com/cicababba/ScreenShareRTCAndroid) you can use the id copied to the clipboard from the app to call and see the remote screen.


## Libraries

### [libjingle peerconnection](https://code.google.com/p/webrtc/)
### [socket.io-client](https://github.com/nkzawa/socket.io-client.java)

## Author

- [Pierre Chabardes](mailto:pierre@chabardes.net)
