biscuit-firmware
================

Customised firmware for RedBear BLE Mini

To change the name of the device, edit simpleBLEPeripheral.c
- static uint8 scanRspData[]
- static uint8 attDeviceName[GAP_DEVICE_NAME_LEN] = "xxxxxx";

TO change the interval, edit simpleBLEPeripheral.c
- DEFAULT_ADVERTISING_INTERVAL

- Install IAR Embedded Workbench
- Copy to C:\Texas Instruments\BLE-CC254x-1.3\Projects
- Make
- Copy the bin file to the device: C:\Texas Instruments\BLE-CC254x-1.3\Projects\ble\SimpleBLEPeripheral-BLEMini\CC2540DB\CC2540DK-BLE Mini UBL\Exe
