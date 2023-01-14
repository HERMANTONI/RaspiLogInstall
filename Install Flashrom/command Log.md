///////////////////////////////////////////////////////////

sudo apt update

sudo apt-get install pciutils-dev

sudo apt-get install zlib1g

sudo apt-get install libftdi-dev

sudo apt-get install libusb-1.0-0-dev

sudo git clone https://github.com/flashrom/flashrom.git

cd flashrom

sudo make install

flashrom


////////////////////////////////////////////////////////////

sudo modprobe spi_bcm2835

sudo modprobe spidev

flashrom -p linux_spi:dev=/dev/spidev0.0,spispeed=1000

////////////////////////////////////////////////////////////

* belum ditest
* cuma baru diinstall saja
