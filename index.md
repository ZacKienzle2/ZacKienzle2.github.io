# rclone backup client

This Google OAuth client lets rclone, on its owner's own server, upload backups
of a market data recording to the owner's Google Drive and read them back. It
requests only the Google Drive `drive.file` scope, so it can see and change only
the files it creates.

Its owner is its only user.

[Privacy policy](privacy.md)
