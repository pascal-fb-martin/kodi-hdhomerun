# kodi-hdhomerun
My own variation on the Silicon Dust's official Kodi addon for their HDHomeRun devices

This addon for Kodi differs from the official HDHomeRun in the way it discovers the HDHomeRun devices: instead of just using the local UDP broadcast method, it also lets the user configure one HDHomeRun device manually, through the addon configuration dialog.

This change allows using the addon through a firewall that blocks the UDP discovery.

The configuration requires one additional item: a space-separated list of network names (or IP addresses) of the devices. The addon will retrieve all other necessary information from each device.

Apart from the configuration item above, there is no change to the addon user interface.

The latest sources of the original addon were obtained from:

https://kodi.tv/addon/scripts-video-add-ons/hdhomerun
