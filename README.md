# MountCheck
Checks a server (Solaris or Linux) to ensure all mounts are present and that no filesystems are read-only
check for any unmounted filesystems which are meant to be online (ufs, vxfs, zfs, nfs for Solaris and ext*, nfs for Linux)
check for read-only filesystems

cifs functionality still to be added (for exports)
nfs export functionality to be added

how to run:
just execute the script, either locally by hand or using whatever automation tools are available.
outputs to stdout - green is good and red is bad!
