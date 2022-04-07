# UEVtube
Open Source Vtubing toolset made for use with the game engine Unreal Engine 5, I've made this tool with the goal of making a completely free and accesable option for 3D Vtubing, VRM importing built it but is possible with a fair bit of modification to run all systems on any FBX skeletal mesh.
## Features
- Camera and lighting controls
- Granular configuration for each of a morph target/blendshape to be bound to a face tracker's output data, or a microphone's inputs audio Visemes.
- Hosts a local server to connect to twitch.tv pubsub, and irc chat, as well as providing functionality for their events.
## Usage Guide
Download a release from the releases tab or run project itself within Unreal Engine 5
UEVtube's main functionality consists of using a mobile phone face tracking app to send face tracking data to the program
### Step 1: Download a face tracker
|Device|Tracker
|----|----|
Android|UEVtube APK https://github.com/KeiraTheCat/UEVtubeTracker, not on play store yet.
iPhone X and newer| LiveLink Face
### Step 2: Connect tracking to UEVtube.
<details><summary>ANDROID</summary>
<p>
  
- Write down local Ip and port in UEVtube and click the "Set" button

![image](ReadMeStuff/guideImage1.png)
- Enter local IP and port into UEVtube Android app and click start

![image](ReadMeStuff/guideImage2.png)
</p>
</details>
<details><summary>IPHONE</summary>
<p>
  
- Write down local IP in UEVtube DISREGARD THE PORT AND IGNORE THE SET BUTTON

![image](ReadMeStuff/guideImage3.png)
  
- Enter the local IP into the Livelink Face app. DO NOT ENTER PORT.

- As of writing this, Livelink face does not support head position, so turn on head position from rotation setting in the avatar config, if you use an included config you will have to set this and save it after loading the included config!
  
![image](ReadMeStuff/guideImage4.png)
</p>
</details>

### Step 3: Load your VRM model.
## License
This project makes use of multiple third party plugins and is itself licensed under the MIT license.
|Plugin|Link|License|
|----|----|----|
|UEVtube | https://github.com/KeiraTheCat/UEVtube | MIT License
|Oculus Lipsync Unreal Integration v29|https://developer.oculus.com/documentation/unreal/audio-ovrlipsync-unreal/|Oculus SDK License|
|TwitchInteractionUE| https://github.com/zeplin455/TwitchInteractionUE |MIT License
|VRM4U| https://github.com/ruyo/VRM4U|MIT License|
|assimp| https://github.com/assimp/assimp |3-clause BSD-License|
|ruyo/assimp| https://github.com/ruyo/assimp |3-clause BSD-License|
|EasyFileDialog|https://github.com/unrealsumon/EasyFileDialog||
|JsonLiveLink|https://github.com/ue4plugins/JSONLiveLink|MIT License|
