```
git clone https://github.com/skogsmaskin/ft6x06_ts
cd ft6x06_ts
make
sudo cp ft6x06_ts.ko /lib/modules/[KERNEL-VERSION]/kernel/drivers/input/touchscreen/
sudo depmod -a
modprobe ft6x06_ts
```

