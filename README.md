# vdev_id.conf

Put this at `/etc/zfs/vdev_id.conf`

Run `udevadm trigger` to update the `/dev/disk/by-vdev/`

To see the update, run `ls -la /dev/disk/by-vdev/`
