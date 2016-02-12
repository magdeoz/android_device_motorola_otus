#Magdeoz TWRP tree for Moto E 3G (2015)

##Building:
````
source build/envsetup.sh
lunch omni_otus-userdebug
make clean
make installclean
make -j10 recoveryimage
````
