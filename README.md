# reset_to_usb
Step for resetting usb in linux

####sudo wipefs --all /dev/sdb
####choose dos filesystem in
####sudo cfdisk /dev/sdb
####create primary partition and write the partition
####sudo mkfs.vfat -n 'NAME' /dev/sdb1   !! capital letters should be used..
####sync
