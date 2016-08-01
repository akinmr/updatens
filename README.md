# updatens
DIY dynamic DNS update script

## How to use
1. Configure your name server so that you can update entry using nsupdate command
2. Put this script to somewhere outside of your dynamic IP host (e.g. your nameserver) and make sure you can use nsupdate from that host
3. Add crontab entry (sample.crontab) to your dynamic IP host
