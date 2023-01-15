///////////////////////////////////////////////////////////
https://www.flashrom.org/Downloads

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
https://www.flashrom.org/RaspberryPi

sudo modprobe spi_bcm2835

sudo modprobe spidev

flashrom -p linux_spi:dev=/dev/spidev0.0,spispeed=1000

////////////////////////////////////////////////////////////

* belum ditest
* cuma baru diinstall saja

////////////////////////////////////////////////////////////
flashrom -p linux_spi:dev=/dev/spidev0.0,spispeed=512
flashrom v1.2-1149-g0bc84bfe on Linux 5.4.51-v7+ (armv7l)
flashrom is free software, get the source code at https://flashrom.org

Using clock_gettime for delay loops (clk_id: 1, resolution: 1ns).
Found Eon flash chip "EN25F80" (1024 kB, SPI) on linux_spi.
===
This flash part has status UNTESTED for operations: WP
The test status of this chip may have been updated in the latest development
version of flashrom. If you are running the latest development version,
please email a report to flashrom@flashrom.org if any of the above operations
work correctly for you with this flash chip. Please include the flashrom log
file for all operations you tested (see the man page for details), and mention
which mainboard or programmer you tested in the subject line.
Thanks for your help!
No operations were specified.
pi@raspberrypi:~ $ sudo ./flashrom -p linux_spi:dev=/dev/spidev0.0 -r test.rom
sudo: ./flashrom: command not found
pi@raspberrypi:~ $ flashrom -p linux_spi:dev=/dev/spidev0.0 -r test.rom
flashrom v1.2-1149-g0bc84bfe on Linux 5.4.51-v7+ (armv7l)
flashrom is free software, get the source code at https://flashrom.org

Using clock_gettime for delay loops (clk_id: 1, resolution: 1ns).
Using default 2000kHz clock. Use 'spispeed' parameter to override.
Found Eon flash chip "EN25F80" (1024 kB, SPI) on linux_spi.
===
This flash part has status UNTESTED for operations: WP
The test status of this chip may have been updated in the latest development
version of flashrom. If you are running the latest development version,
please email a report to flashrom@flashrom.org if any of the above operations
work correctly for you with this flash chip. Please include the flashrom log
file for all operations you tested (see the man page for details), and mention
which mainboard or programmer you tested in the subject line.
Thanks for your help!
Reading flash... done.

