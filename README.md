# Synology_Photos_Face_Patch
Synology Photos Facial Recognization Patch

## Here is my Chinese blog to show how to patch
https://blog.jinlife.com/index.php/archives/49/

## This patch will ignore GPU and let DS918+ to have facial recognization function in Synology Photos

## DS3615xs don't need this patch.
## DS918+ already support facial recognization don't need this patch

# Use it at your own risk, you might lose data with this patch.

## Download this file and upload to home folder in Synology
## SSH connect to Synology and input below command to patch the file.
```bash
cp /volume1/homes/jinlife/libsynophoto-plugin-model.so /var/packages/SynologyPhotos/target/usr/lib/ 
```