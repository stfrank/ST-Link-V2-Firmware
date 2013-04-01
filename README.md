# ST-Link/V2-Firmware
Documentation for the retrieval and recovery of corrupt ST-Link/V2 firmwares for both the [standalone](http://www.st.com/web/catalog/tools/FM146/CL1984/SC724/SS1677/PF251168) and embedded (e.g. DISCOVERY boards) ST-Link/V2 in-circuit programmer/debuggers.

# Objectives
1. Retrieve the available ST-Link/V2 firmwares
2. Recovery USB DFU protocol and application

# External Resources
### STM
* [AN3156](http://www.st.com/st-web-ui/static/active/jp/resource/technical/document/application_note/CD00264379.pdf) USB DFU protocol used in the STM32TM bootloader
 * [AN3155](http://www.stmcu.org/download/index.php?act=down&id=2906) USART STM32 bootloader protocol
 * AN3154 CAN bootloader protocol
* [AN2606](http://www.st.com/st-web-ui/static/active/en/resource/technical/document/application_note/CD00167594.pdf) STM32TM microcontroller system memory boot mode

### Community
* texane [stlink](https://github.com/texane/stlink)
* D. Becker [arm-utilities](https://code.google.com/p/arm-utilities/)
 * [stlinkv2-util.c](https://code.google.com/p/arm-utilities/source/browse/trunk/stlink-download/stlinkv2-util.c)
* G. McRae (spacevs) [stm32flash](https://code.google.com/p/stm32flash/)
* Taylor Killian: [Retrieving ST-Link/V2 Firmware from Update Utility](http://www.taylorkillian.com/2013/01/retrieving-st-linkv2-firmware-from.html)
 * Requires editing.
