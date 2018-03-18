# kodi-hdhomerun
My own variation on the Silicon Dust's official Kodi addon for their HDHomeRun devices

This addon for Kodi differs from the official HDHomeRun in the way it discovers the HDHomeRun devices: instead of just using the local UDP broadcast method, it also accesses the hdhomerun.com web site.

This change allows using the addon even through a firewall that blocks the UDP discovery.

(The HDHomeRun devices call home, getting firmware updates, but also apparently registering themselves. The Silicon Dust web site must log the initiator's IP address or something similar, since the web page URL used for the discovery is constant and contains no differentiating information.)

There is no change to the addon configuration or user interface. The addon behaves the exact same way.
