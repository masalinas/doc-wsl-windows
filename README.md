# Description
Documentation WSL2 in windows

## Select the distribution to be installed

From ofitial Ubuntu site select the Ubuntu to be installed

https://github.com/masalinas/doc-wsl-windows.git

## Import distribution selected

```
wsl --import <Distribution Name> <Installation Folder> <Ubuntu WSL2 Image Tarball path>
```

where:
- **<Distribution Name>** is the name to new distrinution example: ubuntu-k3s
- **<Installation Folder>** is the folder in windows where the new distribution will be installed: C:\Users\masal\Documents\ubuntu-k3s
- **Ubuntu WSL2 Image Tarball path>** is the relative of absolute path where download the tar ball for the distribution: C:\Users\masal\Downloads\ubuntu-20.04-server-cloudimg-amd64-wsl.rootfs.tar.gz

By default the unique user account created is root

## Start distribution

```
 wsl -d ubuntu-k3s genie -s
```
