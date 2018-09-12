# disco_l475_iot1-ISM43362-WIFI-Zephyr-12.0
Inventek ISM3243362 wifi Ported to Zephyr 12.0  

To build wifi_scan example go to samples/net/wifi_scan.
follow below steps
NOTE cmake version 3.8.2 used.

cd $ZEPHYR_BASE/samples/hello_world
mkdir build && cd build

# On Windows
cd %ZEPHYR_BASE%\samples\hello_world
mkdir build & cd build


# Use cmake to configure a Ninja-based build system:
cmake -GNinja -DBOARD=disco_l475_iot1 ..

# Now run ninja on the generated build system:
ninja
ninja flash
