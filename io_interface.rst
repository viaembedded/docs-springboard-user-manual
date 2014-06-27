.. _io-interface:

*************
I/O Interface
*************

The VIA VAB-600 has a wide selection of interfaces integrated into the board.
It includes a selection of frequently used ports as part of the external I/O
coastline.

External I/O Ports
------------------

.. _figure-external-io:
.. figure:: images/external_io.*
   :align: center
   :alt: External I/O ports

   External I/O ports

Layout diagram description table of external rear I/O ports:

==== ========================
Item Description
==== ========================
1    CN12: DC-In jack
2    SD1: Micro SD card slot
3    USB2: Mini USB 2.0 port 2 (type AB port)
4    USB2: Mini USB 2.0 port 1 (type AB port)
5    HDMI1: Mini HDMI® port
6    LAN1: RJ-45 (Fast Ethernet) LAN port
==== ========================


DC-In Jack
~~~~~~~~~~

The mainboard comes with a coaxial power connector on the real I/O panel
adjacent to the Micro SD slot. The power connector carriers +12VDC ~ +24VDC
external power input. The specifications and pinout of the power connector
are shown below.

.. _figure-dc-in-jack:
.. figure:: images/dc-in_jack.*
   :align: center
   :alt: DC-In jack diagram

   DC-In jack diagram

+------------------------------+
|Physical Specifications       |
+=================+============+
|Outer Diameter   |3.7 mm      |
+-----------------+------------+
|Inner Diameter   |1.3 mm      |
+-----------------+------------+
|Barrel Depth     |8.25 mm     |
+-----------------+------------+

+-----------------+------------+
|Electrical Specifications     |
+=================+============+
|Input Voltage    |+12V ~ +24V |
+-----------------+------------+


Micro SD Card Slot
~~~~~~~~~~~~~~~~~~

The Micro SD card slot is located on the rear I/O panel, it offers expandable
storage.

.. _figure-sd-card:
.. figure:: images/sd_card.*
   :align: center
   :alt: Micro SD Card slot diagram

   Micro SD Card slot diagram

Micro SD Card slot pinout:

=== ===========
Pin Signal
=== ===========
1   SD0DATA2
2   SD0DATA3
3   SD0CMD
4   VDD (3.3V)
5   SD0CLK
6   GND
7   SD0DATA0
8   SD0DATA1
9   SD0_CD
=== ===========

Mini USB 2.0 Port
~~~~~~~~~~~~~~~~~

There are two integrated Mini USB 2.0 ports located on the rear I/O panel. The
Mini USB 2.0 interface port gives complete Plug and Play and hot swap
capabilities for external devices and it complies with USB UHCI, rev. 2.0. Each
Mini USB port uses the USB Type AB receptacle port connector. The pinout of
the typical Mini USB port is shown below.

.. _figure-mini-usb:
.. figure:: images/mini_usb.*
   :align: center
   :alt: Mini USB port diagram

   Mini USB port diagram

Mini USB 2.0 port pinout:

=== ========= === =========
Pin Signal    Pin Signal
=== ========= === =========
1   VCC (+5V) 1   VCC (+5V)
2   USBH1-    2   USBH2-
3   USBH1+    3   USBH2+
4   ID (GND)  4   ID (GND)
5   GND       5   GND
=== ========= === =========

Mini HDMI® Port
~~~~~~~~~~~~~~~

The integrated 19-pin Mini HDMI port uses an HDMI Type C receptacle
connector as defined in the HDMI specification. The Mini HDMI port is for
connecting to HDMI displays. The pinout of the Mini HDMI port is shown
below.

.. _figure-hdmi:
.. figure:: images/hdmi.*
   :align: center
   :alt: Mini HDMI® port diagram

   Mini HDMI® port diagram

Mini HDMI® port pinout:

=== ========= === =========
Pin Signal    Pin Signal
=== ========= === =========
1   GND       2   LCD1DO2+
3   LCD1DO2-  4   GND
5   LCD1DO1+  6   LCD1DO1-
7   GND       8   LCD1DO0+
9   LCD1DO0-  10  GND
11  LCD1CLK+  12  LCD1CLK-
13  GND       14  HDMI_CECIN
15  DDCSCL    16  DDCSDA
17  ✗         18  VCC_5V
19  HPD             
=== ========= === =========


RJ-45 LAN port (Fast Ethernet)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The integrated 8-pin Fast Ethernet port is using an 8 Position 8 Contact (8P8C)
receptacle connector (commonly referred to as RJ-45). The Fast Ethernet ports
are controlled by VIA VT6113 10/100 Base-TX PHY chip controller. The
pinout of the Fast Ethernet port is shown below.

.. _figure-fast-ethernet:
.. figure:: images/fast_ethernet.*
   :align: center
   :alt: Fast Ethernet port diagram

   Fast Ethernet port diagram

Fast Ethernet port pinout :

==== =========
Pin  Signal
==== =========
1    TD+
2    TD-
3    RD+
4    REGOUT
5    REGOUT
6    RD-
7    GND
8    GND
==== =========

The RJ-45 port has two individual LED indicators located on the front side to
show its Active/Link status and Speed status.

Fast Ethernet LED color definition:

+--------------+------------------------------------+----------------------------------+
|              |Link LED                            |Active LED                        |
|              |(Left LED on RJ-45 connector)       |(Right LED on RJ-45 connector)    |
+==============+====================================+==================================+
|Link Off      |Off                                 |Off                               |
+--------------+------------------------------------+----------------------------------+
|Speed_10Mbit  |The LED is always On in dark color  |Flash in Yellow or Orange color   |
+--------------+------------------------------------+----------------------------------+
|Speed_100Mbit |The LED is always On in Red color   |Flash in Yellow or Orange color   |
+--------------+------------------------------------+----------------------------------+


Onboard Connectors
------------------

DC-In Connector
~~~~~~~~~~~~~~~

The mainboard has an onboard DC-In 2-pin power connector to connect the
DC-In power cable. The DC-In power connector is an optional power
connector in addition to the DC-In jack on the rear IO panel. This provides
two methods for delivering +12VDC ~ +24VDC to the mainboard. The pinout of
the DC-In connector is shown below.

.. _figure-dc-in:
.. figure:: images/dc-in.*
   :align: center
   :alt: DC-In connector diagram

   DC-In connector diagram

DC-In connector pinout:

==== =========
Pin  Signal
==== =========
1    +12VDC ~ +24VDC
2    GND
==== =========

SIM Card Slot
~~~~~~~~~~~~~

The mainboard is equipped with a SIM card slot located on the top side of the
board which can support a 3G SIM card. Using the SIM card slot on VAB-600
requires a 3G module installed in the Mini Card expansion slot to enable the
3G function, otherwise the SIM card slot is disabled. The SIM card slot is
designed only for 3G module without built-in SIM card slot on it. The SIM
card slot is labeled as "SIM1". The pinout of the slot is shown below.

.. _figure-sim-slot:
.. figure:: images/sim_slot.*
   :align: center
   :alt: SIM card slot diagram

   SIM card slot diagram

SIM card slot pinout:

==== =============
Pin  Signal
==== =============
1    USIM_VCC
2    USIM_RST
3    USIM_CLK
4    ✗
5    GND
6    USIM_VPPSIM
7    USIM_DATA
==== =============


Battery Charger Connector (Optional)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The mainboard is equipped with an onboard battery charger connector used
for connecting the external cable for charging a rechargeable battery. The
battery charger connector is labeled as "CN3". The connector pinout is shown
below.

.. _figure-battery-charger:
.. figure:: images/battery_charger.*
   :align: center
   :alt: Battery Charger connector diagram

   Battery Charger connector diagram

Battery charger pinout:

==== =============
Pin  Signal
==== =============
1    Voltage detect
2    I2C0SCL
3    I2C0SDA
4    GND
5    Temperature Detect
==== =============

RTC Battery Connector
~~~~~~~~~~~~~~~~~~~~~

The mainboard is equipped with an onboard RTC battery connector used for
connecting the external cable battery that provides power to the 32.768KHz
crystal oscillator for Real Time Clock (RTC). The RTC battery connector is
labeled as "BAT1". The connector pinout is shown below.

.. _figure-rtc-connector:
.. figure:: images/rtc_connector.*
   :align: center
   :alt: RTC Battery connector diagram

   RTC Battery connector diagram

RTC Battery connector pinout:

==== =============
Pin  Signal
==== =============
1    +VBAT
2    GND
==== =============

Front Panel Pin Header
~~~~~~~~~~~~~~~~~~~~~~

The front panel pin header block consists of 6 pins. It provides access to the
system power LED, power switch and shut down switch. The front panel pin
header is labeled as "CN7". The pinout of the pin header is shown below.

.. _figure-front-panel:
.. figure:: images/front_panel.*
   :align: center
   :alt: Front Panel pin header diagram

   Front Panel pin header diagram

Front Panel pin header pinout:

==== ========== ==== ==========
Pin  Signal     Pin  Signal
==== ========== ==== ==========
1    PWR_LED    2    GND
3    PWRBTN-    4    GND
5    RESET1     6    GND
==== ========== ==== ==========

.. note::

   Although the signal name for pin#5 is "RESET1", its function is "shut down".

GPIO and I²C Pin Header
~~~~~~~~~~~~~~~~~~~~~~~

The GPIO and I²C combination pin header block labeled as "CN9" is used for
connecting the I²C device, and eight General Purpose Input and Output. The
pinout of the combination pin header is shown below.

.. _figure-gpio-i2c:
.. figure:: images/gpio_i2c.*
   :align: center
   :alt: GPIO and I²C pin header diagram

   GPIO and I²C pin header diagram

GPIO and I²C pin header pinout:

==== ========== ==== ==========
Pin  Signal     Pin  Signal
==== ========== ==== ==========
1    VCC33      2    VCC_5V
3    GND        4    VSUS33
5    GPI20_CH   6    GPIO24_CH
7    GPIO21     8    GPIO25
9    GPIO_22    10   GPIO_26
11   GPIO_23    12   GPIO_27
13   I2C0SDA    14   I2C0SCL
==== ========== ==== ==========

SPI Flash Connector
~~~~~~~~~~~~~~~~~~~

The mainboard has one 8-pin SPI flash connector. By connecting to the SPI
BIOS programming fixture, the SPI (Serial Peripheral Interface) flash connector
can update the SPI flash ROM. The connector is labeled as "SPI1". The pinout
of the connector is shown below.

.. _figure-spi:
.. figure:: images/spi.*
   :align: center
   :alt: SPI Flash connector diagram

   SPI Flash connector diagram

SPI Flash connector pinout:

==== =================
Pin  Signal
==== =================
1    ✗
2    SFCS1 (Reserved)
3    SFDO
4    SFDI
5    SFCLK
6    SFCS0-
7    GND
8    VPROG_SP1 (3.3V)
==== =================

USB Connector
~~~~~~~~~~~~~

The mainboard includes one onboard USB connector designed for connecting
the wireless LAN USB module. The connector is labeled as "CN11". The
pinout of the connector is shown below.

.. _figure-usb:
.. figure:: images/usb.*
   :align: center
   :alt: USB connector diagram

   USB connector diagram

USB connector pinout:

==== =================
Pin  Signal
==== =================
1    +5V
2    USBH3-
3    USBH3+
4    GND
5    USB_WIFI_LED
6    GPIO_4
==== =================

COM Connector
~~~~~~~~~~~~~

There are two onboard COM connectors on the top side of the mainboard.
The COM connectors labeled as "COM1" and "COM2" are used to attach
additional COM port that supports Tx/Rx. The pinout of the COM connectors
are shown below.

.. _figure-com:
.. figure:: images/com.*
   :align: center
   :alt: COM connector diagram

   COM connector diagram

COM connector pinout:

+--------------+--------------+
| COM1         | COM2         |
+-----+--------+-----+--------+
| Pin | Signal | Pin | Signal |
+=====+========+=====+========+
|1    | TXD0   |1    | TXD2   |
+-----+--------+-----+--------+
|2    | RXD0   |2    | RXD2   |
+-----+--------+-----+--------+
|3    | GND    |3    | GND    |
+-----+--------+-----+--------+
|4    | RTS0   |4    | RTS2   |
+-----+--------+-----+--------+
|5    | CTS0   |5    | CTS2   |
+-----+--------+-----+--------+

Front Audio Pin Header
~~~~~~~~~~~~~~~~~~~~~~

The mainboard has a front audio pin header for connecting the Line-Out, Line-
In and Mic-In jacks. The pin header is labeled as “CN8”. The pinout of the pin
header is shown below.

.. _figure-audio:
.. figure:: images/audio.*
   :align: center
   :alt: Front audio pin header diagram

   Front audio pin header diagram

Front audio pin header pinout:

==== ========== ==== ==========
Pin  Signal     Pin  Signal
==== ========== ==== ==========
1    LINEIN_R   2    GND
3    LINEIN_L   4    MICIN1
5    LINEOUT_R  6    MICIN2
7    LINEOUT_L  8    HP_DET
==== ========== ==== ==========

Mini Card Slot
~~~~~~~~~~~~~~

The VAB-600 mainboard is equipped with a Mini card expansion slot labeled
as "CN2". The Mini card slot is used to attach the USB connectivity 3G module
to provide 3G function. The pinout of the slot is shown below.

.. _figure-mini-card:
.. figure:: images/mini_card.*
   :align: center
   :alt: Mini Card slot diagram

   Mini Card slot diagram

Mini Card slot pinout:

==== ========== ==== ==========
Pin  Signal     Pin  Signal
==== ========== ==== ==========
1    ✗          2    VSUS33
3    ✗          4    GND
5    ✗          6    +1.5V
7    ✗          8    USIM_VCC
9    GND        10   USIM_DATA
11   ✗          12   USIM_CLK
13   ✗          14   USIM_RST
15   GND        16   USIM_VPP
17   ✗          18   GND
19   ✗          20   -W_DISABLE_1
21   GND        22   -PEX1_RST
23   ✗          24   VSUS33
25   ✗          26   GND
27   GND        28   +1.5V
29   GND        30   I2C0SCL
31   ✗          32   I2C0SDA
33   ✗          34   GND
35   GND        36   USBHD_0-
37   GND        38   USBHD_0+
39   VSUS33     40   GND
41   VSUS33     42   LED_WWAN1-
43   GND        44   LED_WLAN1-
45   ✗          46   LED_WPAN1-
47   ✗          48   +1.5V
49   ✗          50   GND
51   ✗          52   VSUS33
==== ========== ==== ==========


4-Wire Resistive Touch Screen Connector
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The mainboard is equipped with a touch screen connector for connecting the
4-wire resistive touch panel. The touch screen connector is labeled as "TS1".
The pinout of the connector is shown below.

.. _figure-four-wire:
.. figure:: images/four-wire.*
   :align: center
   :alt: 4-Wire Resistive Touch Screen connector diagram

   4-Wire Resistive Touch Screen connector diagram

4-Wire Resistive Touch Screen connector pinout:

==== ==========
Pin  Signal
==== ==========
1    TPXP
2    TPYP
3    TPXM
4    TPYM
==== ==========

Key PAD Connector
~~~~~~~~~~~~~~~~~

The mainboard is equipped with a Key PAD connector for connecting the
keypad device. The connector is labeled as “KPAD1”. The pinout of the
connector is shown below.

.. _figure-key-pad:
.. figure:: images/key_pad.*
   :align: center
   :alt: Key PAD Connector diagram

   Key PAD Connector diagram

Key PAD connector pinout:

==== ==========
Pin  Signal
==== ==========
1    VCC33
2    KPADROW0
3    KPADROW1
4    KPADROW2
5    KPADROW3
6    KPADROW4
7    GND
==== ==========

CIR Connector
~~~~~~~~~~~~~

The mainboard provides a CIR (Consumer Infrared Receiver) connector on the
top side of the board. The CIR connector is used to connect the infrared
receiver module to enable infrared wireless interface. The pinout of the CIR
connector is shown below.

.. _figure-cir:
.. figure:: images/cir.*
   :align: center
   :alt: CIR connector diagram

   CIR connector diagram

CIR connector pinout:

==== ==========
Pin  Signal
==== ==========
1    VSUS33
2    GND
3    CIR
==== ==========

DVO Connector
~~~~~~~~~~~~~

The DVO (Digital Video Output) connector works as an interface for multidisplay
devices. This connector allows the mainboad to connect an additional
daughter card which is required for a certain display such as TTL or LVDS
display. The DVO connector is labeled as “CN13”. The pinout of the
connector is shown below.

.. _figure-dvo:
.. figure:: images/dvo.*
   :align: center
   :alt: DVO connector diagram

   DVO connector diagram

DVO connector pinout:

==== =================== ==== ===================
Pin  Signal              Pin  Signal
==== =================== ==== ===================
1    VCC33               26   LD15
2    VCC33               27   GND
3    VCC33               28   LD16
4    5VIN                29   LD17
5    5VIN                30   LD18
6    5VIN                31   LD19
7    VIN (DC-In/Battery) 32   LD20
8    VIN (DC-In/Battery) 33   LD21
9    GND                 34   LD22
10   LD00                35   LD23
11   LD01                36   GND
12   LD02                37   DVP1CLK+
13   LD03                38   GND
14   LD04                39   DVPHS
15   LD05                40   DVPVS
16   LD06                41   DVPDE
17   LD07                42   PWMOUT0
18   GND                 43   TTL_RST
19   LD08                44   I2C0SCL
20   LD09                45   I2C0SDA
21   LD10                46   DVO_CLK
22   LD11                47   DVO_DATA
23   LD12                48   LVDSENBL
24   LD13                49   LVDSENVDD
25   LD14                50   GND
==== =================== ==== ===================

.. warning::

   Please DO NOT plug/unplug a DVO flex cable to /from a DVO connector (CN13) when
   the system is powered-ON or running.
