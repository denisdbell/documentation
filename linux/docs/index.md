# This is my docs for all useful linux commands

## Drives

### Mounting a usb thumbdrive to another location

1. Insert USB thumb drive.
2. Find which mount point its on - `mount | grep media`
3. Remount whereever you want to - `mount -t vfat $(mount | grep 2E25-C3261) ~/Documents/mydrive`

  
