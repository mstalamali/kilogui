# KiloGUI

This version works on Ubuntu 24.04 with Qt 5.

To install the required dependencies run:
```shell
sudo apt install -y libusb-dev libftdi-dev git qtbase5-dev qt5-qmake qtbase5-dev-tools
```

To compile the software run:
```shell
qmake
make -j$(nproc)
```

To run the Kilogui software please run:
```shell
./src/kilogui
```

