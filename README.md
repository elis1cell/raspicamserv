# raspicamserv
Raspberry PI network camera stream server

The <b>raspicamserv</b> project is an open source project providing live video stream over IP network using RTSP/RTP protocols. Is is a part of Open Unniversity of Israel, 20588 Data Communication Workshop requirements for a B.Sc. degree in Computer Science.

Usage:<br>
raspicamserv \<options\><br>
Options:<br>
-? Help information.<br>
-w Set image width \<size\>. Default: 1920.<br>
-h Set image height \<size\>. Default: 1080.<br>
-b Set bitrate (in bits/second).<br>
-o Output filename \<filename\> (to write to stdout, use '=o -').<br>
-v Output verbose information.<br>
-f Specify the frames per second.<br>
-p Specify H264 profile to use for encoding.<br>
