# blinker-qpc
Blinker - example application based on "QP/C RTEF" utilizing "west" for project management.
* QP/C is a lightweight, open source Real-Time Embedded Framework (RTEF) for building modern embedded software.
> More info: https://github.com/QuantumLeaps/qpc
* west is meta tool for the project management. Its origins and use can be found in the Zephyr project.
> More info: https://github.com/zephyrproject-rtos/west

## Getting Started
### Prerequisites
* Python
* west

### Initialize workspace
```
west init -m https://github.com/adamkulpa/blinker-qpc --mr main my-workspace
```

### Update project and fetch modules
```
cd my-workspace
west update
```
