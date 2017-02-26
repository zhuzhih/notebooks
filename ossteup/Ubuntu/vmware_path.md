#vmware patch
##vmware 12+kernel 4.10
```aidl
sudo -s 后运行以下内容打补丁：
# cd /usr/lib/vmware/modules/source
# tar xf vmmon.tar
# mv vmmon.tar vmmon.old.tar
# sed -i 's/uvAddr, numPages, 0, 0/uvAddr, numPages, 0/g' vmmon-only/linux/hostif.c
# tar cf vmmon.tar vmmon-only
# rm -r vmmon-only
# tar xf vmnet.tar
# mv vmnet.tar vmnet.old.tar
# sed -i 's/addr, 1, 1, 0/addr, 1, 0/g' vmnet-only/userif.c
# tar cf vmnet.tar vmnet-only
# rm -r vmnet-only

```