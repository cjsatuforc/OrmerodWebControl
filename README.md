OrmerodWebControl
=================

Web Control Interface for the RepRapPro Ormerod and other RepRaps that support it.

Derived from iamburny's on Github here: https://github.com/iamburny/OrmerodWebControl - much credit to him.

reprap.remote.htm - javascript links point to external CDN's, NO editing required, just rename to reprap.htm and copy to "www" directory on your Ormerod's Duet SD card.

------------------------------------------------------------------------------------------------------------------------

*** Below instruction are only for running the interface from a Local Webserver i.e. req's no internet connection ****

reprap.htm - script src's and link ref's need changing see below, must reside on the Ormerod's Duet SD card this is the only file served by the on board (duet) web server.

favicon.ico
js (dir)
img(dir)
fonts(dir)
css(dir)

All of the above should be stored on a web server local to you.

1. before copying reprap.htm to the SD card edit it and change all link href locations (top of file) and script src locations (end of file) to point to where they reside on your local webserver, you can "find and replace" anything beginning with "//192.168.1.2/reprap".

Dont forget this is a Beta release, some features are missing, some may not work, I recommend you keep a close eye on your Ormerod while operating it via this interface as it has not been fully tested yet.

RepRapPro Ltd
