# scrub-md-devices
Script to periodically scrub linux md devices

# Installation / Usage
Save this script and run it periodically.

```
wget -O /etc/cron.monthly/scrub-md-devices https://raw.githubusercontent.com/jnorell/scrub-md-devices/master/scrub-md-devices
chmod +x /etc/cron.monthly/scrub-md-devices
```

# See Also
https://raid.wiki.kernel.org/index.php/Scrubbing_the_drives

In particular the notes on raid6, if you use that.
