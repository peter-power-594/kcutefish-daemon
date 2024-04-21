# CutefishOS Daemon

CutefishOS backend

## Ubuntu Dependencies:

```shell
sudo apt install cmake libqapt-dev
```

## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make install
```

## Uninstall

```shell
rm /usr/bin/cutefish-daemon
rm /etc/dbus-1/system.d/com.cutefish.Daemon.conf
rm /usr/share/dbus-1/system-services/com.cutefish.Daemon.service
```

## License

This project has been licensed by GPLv3.
