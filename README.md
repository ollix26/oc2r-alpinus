This is a para-fork of oc2r. The only thing that i have (currently) done is exchange the rootfs with alpine linux.
Things working:
  X11
  Networking
  Drives
  Framebuffer devices
  Keyboard input

Non working:
  Import/Export card

Untesed:
  Sound card

To initialize network, run this:
ip link set eth0 up
ip addr add 10.0.2.15/24 dev eth0
ip route add default via 10.0.2.2
echo "nameserver 1.1.1.1" > /etc/resolv.conf
