If you can't access the drive, execute the following command:
```
sudo ntfsfix /dev/sdXY
```
where XY is the partition, e.g sda2 or sdb1

Then, mount with:
```
sudo mount -o rw /dev/sdXY
```
