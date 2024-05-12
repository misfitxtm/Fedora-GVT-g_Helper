Intel Single GPU passthrough GVT-g helper for Fedora / Nobara 39+

For a guide, watch Pavol's video on youtube: https://youtu.be/6-RjFl00QSk

To display your VM, you'll need to download Looking Glass: https://looking-glass.hostfission.com/
To hear the audio from your VM, you'll need Scream: https://github.com/duncanthrax/scream
Alternatively you can pass through a USB sound card to the VM instead. 

To install, first run: chmod +x part_1.sh

Then run: ./part_1.sh
Reboot your computer
run ./part_2.sh

Optionally, to hear audio through the host, run:
./part_3_optional.sh

Sources:
* https://github.com/intel/gvt-linux/wiki/GVTg_Setup_Guide
* https://looking-glass.hostfission.com/wiki/Installation
* https://github.com/duncanthrax/scream

Forked from https://github.com/pavolelsig/Ubuntu_GVT-g_helper
to make it easier to setup on Fedora based distros. 

ONLY TESTED AND WORKING ON FEDORA 39 AND NOBARA LINUX. 
