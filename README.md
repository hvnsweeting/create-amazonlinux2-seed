# create-amazonlinux2-seed

Edit `create-amazonlinux2-seed` to update network config as needed.

Run `./create-amazonlinux2-seed` to generate new seed.iso file.

Make sure to backup/snapshot the original VDI file
https://cdn.amazonlinux.com/os-images/latest/virtualbox/

Create new VM, add IDE CDROM and mount the created seed.iso file.
Boot.

NOTICE: this must be on the **FIRST** boot.


Tested on Amazon Linux 2 LTS 2.0.20210813.1 x86_64 VirtualBox image

Details:

- https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/amazon-linux-2-virtual-machine.html
