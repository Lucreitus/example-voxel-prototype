# example-voxel-prototype
Easy example of a way to view MagicaVoxel models in VR

Use this project as a template for how to easily view your MagicaVoxel prototypes in VR mode. Start a new directory and put your ".ply" model inside of it. Then create a new file in the same directory called "index.html".

If you like, you can copy and paste the index.html from this example into your index.html. Change the value of "src" on line 13 to the name of your file. Change the id to something that make sense for your project and make the value of the "src" on line 16 that id.

To view your project, turn on your local server. The easiest way to do this, is by running `python -m SimpleHTTPServer 8000` from inside your directory on the command line. If this sounds scary and awful, ask me and I'll walk you through it irl.

To view your project on your phone, make sure the phone and the computer you're running your server on are on the same WiFi network. Then, on your computer, navigate to Network, inside of System Preferences. You should see your IP address. In Chrome on your phone, type in the IP address followed by the port you're running your server on. If you followed this example, it should look something like "192.168.XX.XXX:8000"
