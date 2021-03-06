# PineTime doesn't run Linux... But that's OK!

![PineTime Smart Watch](https://lupyuen.github.io/images/pinetime-title.jpg)

> __Update 13 Jul 2020:__ 1️⃣ &nbsp; We are getting ready to factory-preload PineTime with open source FreeRTOS firmware ([ported by JF002](https://github.com/JF002/Pinetime)) and MCUBoot Bootloader ([ported by lupyuen](https://lupyuen.github.io/pinetime-rust-mynewt/articles/mcuboot))... 2️⃣ &nbsp; PineTime Owners may use the [nRF Connect](https://www.nordicsemi.com/Software-and-tools/Development-Tools/nRF-Connect-for-mobile) mobile app (Android / iOS) to update PineTime's firmware and sync PineTime's date/time... 3️⃣ &nbsp; PineTime will be shipped without Flash ROM protection... 4️⃣ &nbsp; We no longer need a Raspberry Pi to remove Flash ROM protection, but I recommend getting an ST-Link v2 ([or compatible](https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20180924134644&SearchText=st-link+v2&switch_new_app=y)) for flashing via SWD... 5️⃣ &nbsp; [Get your PineTime Dev Kit today!](https://store.pine64.org/product/pinetime-dev-kit/)

[__PineTime Smart Watch__](https://wiki.pine64.org/index.php/PineTime) works great with open source embedded software platforms like __Arduino, FreeRTOS, RIOT, Mynewt, wasp-os, Zephyr,__ ... None of which are based on Linux!

Think of PineTime as a supercharged BBC micro:bit (or Arduino Uno) that comes with Bluetooth LE, colour LCD display (240 x 240), touchscreen, heart rate sensor and accelerometer.

__PineTime is incredibly hackable:__ Flash our own firmware, build our own watch faces, render graphics on the touchscreen, ... The PineTime FOSS Community is always happy to help you hack PineTime!

__C is the most common language__ for coding PineTime. If you're familiar with Python, try coding PineTime with __MicroPython on wasp-os.__

If you're into cutting edge coding, check out __Rust Embedded__ (and Real Time For the Masses) on PineTime.

# Some PineTime wiring needed

PineTime ships as a __Developer Kit__... Get ready to do some wiring!

Some newbies find it tricky to connect to the SWD Port inside PineTime, please chat with us online for tips.

I recommend using a __Raspberry Pi to remove Flash ROM protection__ from PineTime (this step is mandatory), also to flash and debug the PineTime firmware.

Advanced firmware coders will find __ST-Link V2__ more efficient for flashing and debugging the firmware. (Though ST-Link V2 can't be used for removing Flash ROM protection)

[More about this in the PineTime Wiki](https://wiki.pine64.org/index.php/PineTime)

# Wireless tools are coming

Programming PineTime the wired way sounds tedious, but we're heading the wireless way...

After installing the wasp-os or Arduino firmware on PineTime (the wired way), we may update the wasp-os / Arduino firmware wirelessly over Bluetooth LE. (wasp-os also exposes the REPL interface wirelessly)

The PineTime FOSS Community is now extending this wireless capability to other types of PineTime firmware, like FreeRTOS, Mynewt and Zephyr.

We have ported to PineTime the open source __MCUBoot Bootloader__, and we have to hope to have it preloaded on PineTime watches soon. 

The new bootloader will let you __switch firmware wirelessly__, like from Mynewt to FreeRTOS. Great for trying out all kinds of experimental firmware created by the PineTime FOSS Community!

With firmware updates over Bluetooth LE, PineTime programming will become so much easier!

# PineTime Companion App

Today we use a mix of mobile apps for firmware flashing and data syncing with PineTime, like DaFlasher and nRF Connect.

The open source __PineTime Companion App__ is under development now. It will run on Android and iOS (via Flutter) and on Linux phones like PinePhone (via GOTK3).  It will probably run on Raspberry Pi and Pinebook Pro too!

The Companion App will update PineTime firmware, sync the date and time, chart your heart rate, push your mobile notifications to PineTime, ... And let you control your smart home gadgets with PineTime!

# What's Next

The PineTime FOSS Community has accomplished so much over the past 6 months because we're all __volunteers passionate about PineTime.__

You're welcome to join us and make the open source PineTime software even better!

[Chat with us on Matrix, Discord, Telegram and IRC](https://wiki.pine64.org/index.php/PineTime#Community)

[My PineTime articles](https://github.com/lupyuen/pinetime-rust-mynewt/blob/master/README.md)

[My RSS Feed](https://lupyuen.github.io/rss.xml)
