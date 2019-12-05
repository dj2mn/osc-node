# OSC-Node

[Raspberry Pi](https://www.raspberrypi.org/) video player controlled by [QLab](http://figure53.com/qlab/) over [OSC](http://opensoundcontrol.org/) written in [Node.js](https://nodejs.org/en/) using [Omxplayer](https://elinux.org/Omxplayer).


### Network

Network Cue Destination Patches:

- Destination: IP address of the Raspberry Pi
- Port: 57121

### OSC message

Available OSC addresses & argements:

- `/play big_buck_bunny.mp4` or `/play /mnt/usb/my-video.mp4`
- `/loop big_buck_bunny.mp4` or `/loop /mnt/usb/my-video.mp4`
- `/stop`
- `/pause` (pause & resume)
- `/cmd "sudo reboot"`

