# Hey! I'm Filing Here

In this lab, I successfully implemented a valid ext2 filesystem containing 2 directories, 1 file, and 1 symbolic link

## Building

```shell
make
```

## Running

to compile
```shell
./ext2-create
```
to mount
```shell
mkdir mnt
sudo mount -o loop cs111-base.img mnt
```

to check contents
```shell
cd mnt
ls
```


## Cleaning up

unmount 
```shell
sudo umount mnt
```
remove directory
```shell
rmdir mnt
```
clean up
```shell
make clean
```
