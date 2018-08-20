# kodi-hdhomerun
My own variation on the Silicon Dust's official Kodi addon for their HDHomeRun devices

This addon for Kodi differs from the official HDHomeRun in the way it discovers the HDHomeRun devices: instead of just using the local UDP broadcast method, it also lets the user configure one HDHomeRun device manually, through the addon configuration dialog.

This change allows using the addon through a firewall that blocks the UDP discovery.

The configuration requires one additional item: the network name (or IP address) of the device. The addon will retrieve all other necessary information from the device itself.

Apart from the configuration item above, there is no change to the addon user interface.
