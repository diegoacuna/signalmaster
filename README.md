# Signalmaster

A simple signaling server for clients to connect and do signaling for WebRTC.

Specifically created as a default connection point for [SimpleWebRTC.js](https://github.com/HenrikJoreteg/SimpleWebRTC)

Read more: 
 - [Introducing SimpleWebRTC and conversat.io](http://blog.andyet.com/2013/feb/22/introducing-simplewebrtcjs-and-conversatio/)
 - [SimpleWebRTC.com](http://simplewebrtc.com)
 - [conversat.io](http://conversat.io)

## Instalation Instructions

 - Clone the repository in your machine:
```bash
git clone https://github.com/diegoacuna/signalmaster.git
```
 - Install node dependencies:
```bash
npm install
```
 - Run:
```bash
node server.js
```
If you want to run the server as a long term process you can use forever:

    npm install forever
    forever start server.js
    forever list
    
