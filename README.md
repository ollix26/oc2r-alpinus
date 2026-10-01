This is a para-fork of oc2r which exchanges minux to alpine

Working:
  Networking, Disks, Projector, Framebuffer, evdev keyboard input,Import/Export Card.

  I've deleted X11 due to save space and make other players be able to actually join the game when near the computer. The operating system can be installed to system using root/setup-disks.sh You will probably need to execute chmod +x setup-disks.sh to make it runable. The default file for the first hard drive is /dev/vdc. APK should work if you set the disk up.

Not tested/working:
  Sound Card
  
