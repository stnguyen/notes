### Automount disks

__No permission problem__

    sudo gedit /etc/fstab

Add the following:

    UUID=2223-1A04    /media/works    vfat  defaults,uid=stefan,gid=stefan,dmask=0027,fmask=0137    0    0
    UUID=8A64-1A04    /media/data    vfat  defaults,uid=stefan,gid=stefan,dmask=0027,fmask=0137    0    0
