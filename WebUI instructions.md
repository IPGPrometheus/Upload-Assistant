
# Welcome to the GUI Wiki

This install is for those who want to have the GUI for UA present on their system.
-
**Standard Installation**

Git clone the repo to your desired folder.

1.1 If you already have a config.py — copy it into your Upload-Assistant/data/* folder.

Update your docker-compose.yml file for desired ports (use the left side) and your desired mounting paths.

In terminal, navigate to the directory:

    cd /path/.../Upload-Assistant/

Then run:

    docker compose up

Enjoy!

Unraid Installation

Make sure you have the Compose plugin installed:
https://forums.unraid.net/topic/38582-plug-in-community-applications

Add New Stack — Name: Upload-Assistant

Click Advanced — set the appdata path to:

    /mnt/user/appdata/Upload-Assistant/
<center> <img src="https://i.ibb.co/zLhG3n6/Picture3.png"  
alt="Compose Stack"  width="380"
style="float: left; margin-right: 10px;" /></center>

Click OK.

Click the Gear Icon next to the stack name → Edit Stack → Compose File.

Copy the docker-compose file from the GitHub repo into the compose editor.
5.1 Update the docker-compose.yml for desired ports (use the left column) and your mount paths.
<center> <img src="https://i.ibb.co/fGxKcJbP/Picture1.png.png"  
alt="Docker Compose"  width=auto
style="float: left; margin-right: 10px;" /></center>

Click Save Changes.

If you want an icon-accessible web link, point it to:

    http://[IP]:yourport
<center> <img src="https://i.ibb.co/SWkSypB/Picture2.png"  
alt="Docker Compose"  width="400"
style="float: left; margin-right: 10px; size: 300px;" /></center>

Click OK and Compose Up.

Once built — enjoy!
