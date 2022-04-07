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
Android|UEVtube APK https://github.com/***REMOVED***/UEVtubeTracker, not on play store yet.
iPhone X and newer| LiveLink Face
### Step 2: Connect tracking to UEVtube.
## License
This project makes use of multiple third party plugins and is itself licensed under the MIT license.
|Plugin|Link|License|
|----|----|----|
|UEVtube | https://github.com/***REMOVED***/UEVtube | MIT License
|Oculus Lipsync Unreal Integration v29|https://developer.oculus.com/documentation/unreal/audio-ovrlipsync-unreal/|Oculus SDK License|
|TwitchInteractionUE| https://github.com/zeplin455/TwitchInteractionUE |MIT License
|VRM4U| https://github.com/ruyo/VRM4U|MIT License|
|assimp| https://github.com/assimp/assimp |3-clause BSD-License|
|ruyo/assimp| https://github.com/ruyo/assimp |3-clause BSD-License|
|EasyFileDialog|https://github.com/unrealsumon/EasyFileDialog||
|JsonLiveLink|https://github.com/ue4plugins/JSONLiveLink|MIT License|
