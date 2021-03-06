..  Copyright (c) 2014-present PlatformIO <contact@platformio.org>
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
       http://www.apache.org/licenses/LICENSE-2.0
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

.. _platform_nordicnrf51:

Nordic nRF51
============
:ref:`projectconf_env_platform` = ``nordicnrf51``

The Nordic nRF51 Series is a family of highly flexible, multi-protocol, system-on-chip (SoC) devices for ultra-low power wireless applications. nRF51 Series devices support a range of protocol stacks including Bluetooth Smart (previously called Bluetooth low energy), ANT and proprietary 2.4GHz protocols such as Gazell.

For more detailed information please visit `vendor site <https://www.nordicsemi.com/eng/Products/nRF51-Series-SoC>`_.

.. contents:: Contents
    :local:

Packages
--------

.. list-table::
    :header-rows:  1

    * - Name
      - Description

    * - `framework-arduinonordicnrf5 <https://github.com/sandeepmistry/arduino-nRF5>`__
      - Arduino Wiring-based Framework (Nordic NRF5 Core)

    * - `framework-mbed <http://mbed.org>`__
      - mbed Framework

    * - `tool-openocd <http://openocd.org>`__
      - OpenOCD

    * - `tool-sreccat <https://github.com/marcows/SRecord>`__
      - Merging tool

    * - `toolchain-gccarmnoneeabi <https://launchpad.net/gcc-arm-embedded>`__
      - gcc-arm-embedded

.. warning::
    **Linux Users**:

        * Install "udev" rules file `99-platformio-udev.rules <https://github.com/platformio/platformio-core/blob/develop/scripts/99-platformio-udev.rules>`_
          (an instruction is located inside a file).
        * Raspberry Pi users, please read this article
          `Enable serial port on Raspberry Pi <https://hallard.me/enable-serial-port-on-raspberry-pi/>`__.


    **Windows Users:**

        Please check that you have a correctly installed USB driver from board
        manufacturer


Frameworks
----------
.. list-table::
    :header-rows:  1

    * - Name
      - Description

    * - :ref:`framework_arduino`
      - Arduino Wiring-based Framework allows writing cross-platform software to control devices attached to a wide range of Arduino boards to create all kinds of creative coding, interactive objects, spaces or physical experiences.

    * - :ref:`framework_mbed`
      - The mbed framework The mbed SDK has been designed to provide enough hardware abstraction to be intuitive and concise, yet powerful enough to build complex projects. It is built on the low-level ARM CMSIS APIs, allowing you to code down to the metal if needed. In addition to RTOS, USB and Networking libraries, a cookbook of hundreds of reusable peripheral and module libraries have been built on top of the SDK by the mbed Developer Community.

Boards
------

.. note::
    * You can list pre-configured boards by :ref:`cmd_boards` command or
      `PlatformIO Boards Explorer <http://platformio.org/boards>`_
    * For more detailed ``board`` information please scroll tables below by
      horizontal.

BBC
~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``bbcmicrobit``
      - `BBC micro:bit <https://developer.mbed.org/platforms/Microbit/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 16 MHz
      - 256 Kb
      - 16 Kb

    * - ``bbcmicrobit_b``
      - `BBC micro:bit B(S130) <https://developer.mbed.org/platforms/Microbit/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - 
      - NRF51822
      - 16 MHz
      - 256 Kb
      - 16 Kb

BluzDK
~~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``bluz_dk``
      - `BluzDK <https://bluz.io/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 32 MHz
      - 256 Kb
      - 32 Kb

Delta
~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``dfcm_nnn40``
      - `Delta DFCM-NNN40 <https://developer.mbed.org/platforms/Delta-DFCM-NNN40/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 32 MHz
      - 256 Kb
      - 32 Kb

JKSoft
~~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``wallbot_ble``
      - `JKSoft Wallbot BLE <https://developer.mbed.org/platforms/JKSoft-Wallbot-BLE/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 16 MHz
      - 128 Kb
      - 16 Kb

Nordic
~~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``nrf51_dk``
      - `Nordic nRF51-DK <https://developer.mbed.org/platforms/Nordic-nRF51-DK/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 32 MHz
      - 256 Kb
      - 32 Kb

    * - ``nrf51_dongle``
      - `Nordic nRF51-Dongle <https://developer.mbed.org/platforms/Nordic-nRF51-Dongle/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 32 MHz
      - 256 Kb
      - 32 Kb

    * - ``nrf51_mkit``
      - `Nordic nRF51822-mKIT <http://developer.mbed.org/platforms/Nordic-nRF51822/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 16 MHz
      - 128 Kb
      - 16 Kb

OSHChip
~~~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``oshchip``
      - `OSHChip <http://oshchip.org/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 32 MHz
      - 256 Kb
      - 32 Kb

RFduino
~~~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``rfduino``
      - `RFduino <http://www.rfduino.com/product/rfd22102-rfduino-dip/index.html>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 16 MHz
      - 128 Kb
      - 8 Kb

RedBearLab
~~~~~~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``redBearLab``
      - `RedBearLab nRF51822 <https://developer.mbed.org/platforms/RedBearLab-nRF51822/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 16 MHz
      - 256 Kb
      - 16 Kb

    * - ``redBearLabBLENano``
      - `RedBearLab BLE Nano 1.5 <https://developer.mbed.org/platforms/RedBearLab-BLE-Nano/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 16 MHz
      - 256 Kb
      - 32 Kb

SeeedStudio
~~~~~~~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``seeedArchBLE``
      - `Seeed Arch BLE <https://developer.mbed.org/platforms/Seeed-Arch-BLE/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 16 MHz
      - 128 Kb
      - 16 Kb

    * - ``seeedArchLink``
      - `Seeed Arch Link <https://developer.mbed.org/platforms/Seeed-Arch-Link/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 16 MHz
      - 256 Kb
      - 16 Kb

    * - ``seeedTinyBLE``
      - `Seeed Tiny BLE <http://developer.mbed.org/platforms/Seeed-Tiny-BLE/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 16 MHz
      - 256 Kb
      - 16 Kb

Switch Science
~~~~~~~~~~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``hrm1017``
      - `Switch Science mbed HRM1017 <https://developer.mbed.org/platforms/mbed-HRM1017/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 16 MHz
      - 256 Kb
      - 16 Kb

    * - ``ty51822r3``
      - `Switch Science mbed TY51822r3 <https://developer.mbed.org/platforms/Switch-Science-mbed-TY51822r3/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 32 MHz
      - 256 Kb
      - 32 Kb

Waveshare
~~~~~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``waveshare_ble400``
      - `Waveshare BLE400 <http://www.waveshare.com/wiki/BLE400>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 32 MHz
      - 256 Kb
      - 32 Kb

ng-beacon
~~~~~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``ng_beacon``
      - `ng-beacon <https://github.com/urish/ng-beacon>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 32 MHz
      - 256 Kb
      - 32 Kb

y5 design
~~~~~~~~~

.. list-table::
    :header-rows:  1

    * - ID
      - Name
      - Platform
      - Debug
      - Microcontroller
      - Frequency
      - Flash
      - RAM

    * - ``nrf51822_y5_mbug``
      - `y5 nRF51822 mbug <https://developer.mbed.org/platforms/Y5-NRF51822-MBUG/>`_
      - :ref:`Nordic nRF51 <platform_nordicnrf51>`
      - :ref:`Yes <piodebug>`
      - NRF51822
      - 16 MHz
      - 256 Kb
      - 16 Kb

.. include:: nordicnrf51_extra.rst
