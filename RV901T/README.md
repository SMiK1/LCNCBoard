RV901T Receiver Card
===============
The Linsn RV901T HUB75 LED driver card has a Spartan 6 LX16 FPGA.

Annotated PCB
-------------

![RV901T Front View](./hardware/front_annotated.jpg)


The Linsn RV901T contains a user-reprogrammable Spartan 6 FPGA (LX16, 14k 'logic cells', 9112 LUTs) and 2x GbE, it has 
potential to be usable as a general purpose FPGA development board, an interface card for various purposes, 
or a logic analyzer.




Getting start
--------
Modify
--------

Hardware
--------
There is [hardware documentation](./hardware/README.md) available, which includes WIP information about mapping from the FPGA balls / IO 
into various peripherals on board and connectors.

You can buy these boards from eBay, Aliexpress, Taobao. As of today (2024/02/26), these boards are around €19 
(including S&H) on Aliexpress.



Documentation
-------------

* [Reverse engineered RV901T Hardware Documentation](./doc/hardware.md)
* [Reverse engineered HUB75B Hat Hardware Documentation](./doc/hub75b_hat.md)
* [Reverse engineered HUB7EB Hat Hardware Documentation](./doc/hub75e_hat.md)
* [Getting Started with the RV901T Board: JTAG Connector and LED blink](./doc/getting_started/getting_started.md)
* [Getting Started with the RV901T Board: Improved JTAG Connector and LED blink](./doc/getting_started/improved_jtag_getting_started.md)
(recomended)

The Improved JTAG Connector uses the JP3 header in a different purpose than
originally planned, providing a stable and solid connection for the JTAG
cable, as well less skills to solder and better electrical interface, as long 
there are lots of ground connections alredy available in the connector.


Acknowledgments
---------------

Thanks to Lucy Fauth and Jana Marie Hemsing for donating two boards and partially tracing out the PHYs, and delayering the PCB.

Thanks to carrotIndustries for assisting with the preliminary RE process at Glühweinprogrammiernacht 2018.

Thanks to enjoy-digital for reverse engineering the RGMII interface, implementing an S6 RGMII PHY interface, and the sample target files.

Thanks to jeanthom for reverse engineering the SDRAM interface.

Thanks for informatic for reverse engineering the HUB75B hat.

Thanks to q3k

License
-------

[CC0](http://creativecommons.org/publicdomain/zero/1.0/") - to the extent possible under law, the person who associated CC0 with this 
work has waived all copyright and related or neighboring rights to this work.


