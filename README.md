# Gotify-Nextcloud-Notifications

This script will read Nextcloud Notifications via API call and push them to [Gotify server](https://github.com/gotify/server). If you do not see any notifications, try to delete lock file, specified in `LOCKFILE`

Please create Application password for this script.

In Gotify Server you have to create an Application and provide API Token to script.

There are 2 modes: `push` and `sync`.

- In case of `push` Notifications from Nextcloud will be pushed to Gotify if you delete notification in Nextcloud or Gotify there will be no reaction.
- In case of `sync` you will have synced notifications stage between both Nextcloud and Gotify, Notification delete in Gotify will cause deletion of this Notification in Nextcloud and opposite.
In Gotify Server you must create a Client Token and provide it to script additionally.

Original place for this script is https://github.com/GAS85/nextcloud_scripts/blob/master/nextcloud-gotify-notifications.sh
