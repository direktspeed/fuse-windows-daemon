# fuse-windows-daemon
Is a Easy Wrapper that allows you to use fuse filesystems inside windows it needs a Lightweight virtual machine to expose a fuse filesystem as sftp share for windows.

## Current State
Its a Draft about how to use a fuse filesystem in windows exposed via ssh connection or samba.
it will use @direktspeed/fs-daemon which can expose a filesystem via ssh or smb nfs share on linux.

## How?
we will offer scripts to create and run @direktspeed/fuse-daemon/build/unikernel inside windows on HyperV, VirtualBox, VMWare, ...many more.
We will also offer exposing the console via ssh for easy administration via the @direktspeed/fuse-daemon/bin/cli




## Resources
- https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/try-hyper-v-powershell
