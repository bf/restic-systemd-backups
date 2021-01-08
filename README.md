# restic-systemd-backups

Automatic restic backups with systemd timer (as a cronjob alternative)

This is an example of systemd-powered restic backup for PostgreSQL and local files.
It will create two backups: One local backup in `/root/backups` and one off-site backup on a custom rsync location.

Please modify `restic-backup.env` as needed.
