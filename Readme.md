My version does not have the bugs from the initial git and I added a barcode functionality.
The video call functio nality does work on android,  iPhone are tricky.

https://github.com/WebDevSimplified/Zoom-Clone-With-WebRTC.git

https://www.youtube.com/watch?v=DvlyzDZDEq4

create a key in the cert folder:
openssl req -new -x509 -key localhost.key -out localhost.cert -days

run the build:
npm run start

install peer:
npm i -g peer

run peer in seperate terminal:
cd cert
peerjs --sslkey localhost.key --sslcert localhost.cert  --port 3001