# bmp
android p2p 1-1 ASCON messaging system. FOSS WICKR contender.

Hello, and welcome to this corner of the interwebs. I just thought up this fun little app idea, and you're welocme to watch me fail at the basics or eventually succeed. Programming = skill + tenacity, my skills are nooby at best and my tenacity has been known to falter, so let's see, shall we.

Let's start with the use case: Two people meet, in person, and want to continue communicating. 
  - One of them has the client installled. NFC "bump" to send play store link / or transmit client data directly via BT
  - Both have client installed. NFC bump to send Unique Identifier (Nick linked to "Public Key") - connection established.
  
  Communication happens when the app is active - there is no central server to bounce anything from. If the network consists of only two persons, that means the app needs to be active on both devices to work. Scalability should be enabled when multiple instances of the app are running and "listening" for bumps. 
  
 # What is a Bump?
 
 Encrypted plaintext in a torrent wrapper. Should be very lightweight, hopefully. Implementing animated emojis is clearly priority Omega. 
 
Projects I will be reading to get this done: 
ASCON Implementation by TU Graz
Confluence https://github.com/arranlomas/Android-Confluence-Wrapper 
NFC Tools https://github.com/nfc-tools/libnfc

Suggestions and / or contributors welcome! 

glhf
