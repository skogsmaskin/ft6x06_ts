git clone https://github.com/skogsmaskin/ft6x06_ts
cd ft6x06_ts
make
sudo cp ft6x06_ts.ko /lib/modules/4.1.17-2-ARCH/kernel/drivers/input/touchscreen/
sudo depmod -a
modprobe ft6x06_ts

