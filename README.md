# kodi-hdhomerun
My own variation on the Silicon Dust's official kodi addon for their HDHomeRun devices

This addon for Kodi differs from the official HDHomeRun in the way it discovers the HDHomeRun devices: instead of just using the local UDP broadcast method, it also lets the user configure one HDHomeRun device manually, through the addon configuration dialog.

The configuration takes 3 additional items:
- The network name (or IP address) of the device.
- The device hexadecimal ID (should be 8 hexadecimal characters, as displayed on the device System Status page (/system.html).
- The authorization string for that device, as displayed by the devices discovery page (/discover.json).

The authorization string is optional: if left empty, the addon cannot access the Silicon Dust TV guide and the channel list of the addon will provide no current or next show information.

Apart from the configuration items listed above, there is no change to the addon user interface.