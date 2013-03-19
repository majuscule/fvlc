redirect pentadactyl (firefox) videos to vlc
============================================

Some streaming videos come packaged in miserable .swf containers that ruin the movie experience. This bash script uses `tcpdump` to listen for the real video stream connection made, and then reopens the stream in VLC.

It's extra cool with [pentadactyl](http://5digits.org/pentadactyl/) or any other plugin that allows you to bind code to browser events. Add a URL listener for websites that you'd prefer to serve video through VLC, starting this script and closing or muting the original tab.

Root privileges are needed to listen to to the network.
