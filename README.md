# RTOS 00

[Docs here](https://github.com/uofu-embed/rtos/tree/main/labs/11.bluetooth)

# Template instructions

When copying this repo as template, make sure the gitmodules are properly initialized. Use the following command to make sure that git sees the .gitmodules file.

```bash
git submodule add git@github.com:FreeRTOS/FreeRTOS-Kernel.git lib/freertos
git submodule add git@github.com:raspberrypi/pico-sdk.git lib/pico-sdk
git submodule add git@github.com:ThrowTheSwitch/Unity.git lib/unity
```

# Cloning instructions 

To close this repository along with the submodules, run this command: 

```bash 
git clone <URL HERE> --recursive
```
