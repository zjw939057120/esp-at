# ESP-AT
./build.py install
./build.py menuconfig

CONFIG_AT_WEB_SERVER_SUPPORT=y
CONFIG_AT_WEB_CAPTIVE_PORTAL_ENABLE=y
CONFIG_LWIP_LOCAL_HOSTNAME="YK-KD"

./build.py build
