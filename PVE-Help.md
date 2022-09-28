## DNS:
If DNS is not resolving correctly, check `/etc/resolv.conf` and make sure the correct DNS server is being used (should be same as router IP most likely).

## Internet:
Changed router or different network?
* Change IP address and gateway address `/etc/network/interfaces`
* Also change `/etc/hosts` to reflect the IP address change
