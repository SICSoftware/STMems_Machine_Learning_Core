# Configuration examples

The *configuration_examples* section of the **Machine Learning Core** repository contains examples showing how to configure the MLC using different tools provided by ST. 

The purpose of these examples is not the final application (dedicated [application examples](../application_examples/) are provided for final applications).  The focus is on the process to configure the MLC, starting from data logs and following all the MLC configuration steps. 

Each folder contains a different configuration procedure depending on the software and hardware used: 

| Example                                                    | Product                                                      | Hardware                                                     | GUI/App                                                      | Machine Learning Tool                                        | Use case                                                     |
| ---------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [*example_0*](./example_0_profi_unico_weka)                | [LSM6DSOX](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dsox.html) | Professional MEMS Tool ([STEVAL-MKI109V3]( https://www.st.com/content/st_com/en/products/evaluation-tools/product-evaluation-tools/mems-motion-sensor-eval-boards/steval-mki109v3.html )) | [Unico GUI](https://www.st.com/en/development-tools/unico-gui.html) | [Unico GUI](https://www.st.com/en/development-tools/unico-gui.html) / Weka | Face-up / Face-down / Shaking                                |
| [*example_1*](./example_1_sensortilebox_stble_unico)       | [LSM6DSOX](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dsox.html) | [SensorTile.box](https://www.st.com/content/st_com/en/products/evaluation-tools/product-evaluation-tools/mems-motion-sensor-eval-boards/steval-mksbox1v1.html) | [STBLESensor](https://www.st.com/content/st_com/en/products/embedded-software/wireless-connectivity-software/stblesensor.html) | [Unico GUI](https://www.st.com/en/development-tools/unico-gui.html) | Yoga pose recognition                                        |
| [*example_2*](./example_2_sensortilebox_algobuilder_unico) | [LSM6DSOX](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dsox.html) | [SensorTile.box](https://www.st.com/content/st_com/en/products/evaluation-tools/product-evaluation-tools/mems-motion-sensor-eval-boards/steval-mksbox1v1.html) | [AlgoBuilder GUI](https://www.st.com/content/st_com/en/products/embedded-software/mems-and-sensors-software/inemo-engine-software-libraries/algobuilder.html) | [Unico GUI](https://www.st.com/en/development-tools/unico-gui.html) | Motion intensity                                             |
| [*example_3*](./example_3_nucleo_unicleo_matlab)           | [LSM6DSRX](https://www.st.com/en/mems-and-sensors/lsm6dsrx.html) | [STM32 Nucleo ](https://www.st.com/content/st_com/en/products/evaluation-tools/product-evaluation-tools/mcu-mpu-eval-tools/stm32-mcu-mpu-eval-tools/stm32-nucleo-boards.html) | [Unicleo GUI](https://www.st.com/en/development-tools/unicleo-gui.html) | [Unico GUI](https://www.st.com/en/development-tools/unico-gui.html) / MATLAB | Face-up / Face-down + Motion intensity                       |
| [*example_4*](./example_4_stwin_stble_unico)               | [ISM330DHCX](https://www.st.com/en/mems-and-sensors/ism330dhcx.html) | [STWIN](https://www.st.com/en/evaluation-tools/steval-stwinkt1b.html) | [STBLESensor](https://www.st.com/content/st_com/en/products/embedded-software/wireless-connectivity-software/stblesensor.html) | [Unico GUI](https://www.st.com/en/development-tools/unico-gui.html) | Fan rack monitoring                                          |
| [*example_5*](./example_5_profi_unico)                     | [LSM6DSOX](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dsox.html) | Professional MEMS Tool ([STEVAL-MKI109V3]( https://www.st.com/content/st_com/en/products/evaluation-tools/product-evaluation-tools/mems-motion-sensor-eval-boards/steval-mki109v3.html )) | [Unico GUI](https://www.st.com/en/development-tools/unico-gui.html) | [Unico GUI](https://www.st.com/en/development-tools/unico-gui.html) | External sensor data in MLC ([LIS2MDL](https://www.st.com/en/mems-and-sensors/lis2mdl.html) magnetometer) |
| [*example_6*](./example_6_sensortilebox_unico_unicleo)     | [LSM6DSOX](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dsox.html) | [SensorTile.box](https://www.st.com/content/st_com/en/products/evaluation-tools/product-evaluation-tools/mems-motion-sensor-eval-boards/steval-mksbox1v1.html) | [Unicleo GUI](https://www.st.com/en/development-tools/unicleo-gui.html) | [Unico GUI](https://www.st.com/en/development-tools/unico-gui.html) | MLC + FSM                                                    |



------



------

**More information: [http://www.st.com](http://st.com/MEMS)**

**Copyright © 2022 STMicroelectronics**