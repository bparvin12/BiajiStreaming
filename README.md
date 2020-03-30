# BiajiStreaming
Site to make your own streaming channel. 

## To get this app up and running on a local machine. In three separate terminal windows: 
1. In the client directory --> `yarn` 
    - installs all the local dependencies 
    `yarn start`
2. In the api directory --> `yarn` --> `yarn start`
    -allows the api to send db streams to a db.json file in the app 
    -dev database environment 
3. In the rtmpserver --> `yarn` --> `yarn start`
    -installs the rtmp server dependencies - node-media-server
    -runs the rtmpserver in the background
    -uses OBS - free and open source video recording and live streaming software
    flv.js