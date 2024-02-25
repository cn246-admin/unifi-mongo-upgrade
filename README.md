# UniFi MongoDB Upgrade

> [!WARNING]
> Please make sure you have backups of your database before proceeding!

This script upgrades MongoDB from 3.6 (and/or 4.0, 4.2) to MongoDB 4.4 on a Debian 11 system.

It may work for other Debian or Ubuntu versions, but I haven't checked.

I used the script I found in the following link as a starting point and got carried away:
https://techblog.nexxwave.eu/update-mongodb-3-6-to-4-4/


This worked perfectly for me on my small homelab UniFi install, and on a Debian 11 VM where I verified my changes to the script.

I can't guarantee anyone else will have the same results.

Please make sure to take and verify backups before using this!


## Links
- https://www.mongodb.com/docs/manual/release-notes/
- https://www.mongodb.com/download-center/community/releases/archive
- https://www.mongodb.com/docs/v5.3/release-notes/4.0-upgrade-standalone/
- https://www.mongodb.com/docs/v5.3/release-notes/4.2-upgrade-standalone/
- https://www.mongodb.com/docs/v5.3/release-notes/4.4-upgrade-standalone/
