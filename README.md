# usbkill 
`usbkill` is an anti-forensic LKM kill-switch that waits for a change on your usb ports and turns off your computer.
usbkill �� anti-forensic ���� ���� Ŀ�� ���  ( Loadable kernel module ,  LKM ) kill-switch�μ� ����� usb��Ʈ�� ��ȭ�� ��ٸ��� ��ȭ�� ����� ��ǻ�͸� �����Ų��.
To run:

```shell
make
sudo insmod usbkill.ko
```

You will need to have the `linux-headers` package installed. If you haven't:

```shell
apt-get install linux-headers-$(uname -r)
```

List usb devices:

```shell
lsusb
```
