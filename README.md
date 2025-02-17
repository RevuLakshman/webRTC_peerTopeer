# webRTC_peerTopeer
Implementing peer to peer audio or video connection using webRTC UDP protocol.

# backend code buils and run steps

 clone the project to local.
 cd > backen folder
 install websocke using belo command
```bash
 npm install websocket
```
 run build
```bash
tsc -build
```
 execute the backend project
```bash
node dist/index.js
```
connect to the websockrt 
https://hoppscotch.io/realtime/websocket and try to connect with default port : ws://localhost:8080
if it gives connection successfull message, ready to go.


#frontend code build and run steps

cd > frontend
install node packages ti local system
```bash
npm install
```
execute the frontend project
npm run dev(react project)
```bash
npm run dev
```
Frontend application will be run on http://localhost:5173/
Finally you can access the sender and reciever using belo
http://localhost:5173/sender
http://localhost:5173/receiver

Once you click on send data button from sender end point camera will be on and data flow will start to reciever via same browser.
make sure websocket connection should be alive throuh out the process.




