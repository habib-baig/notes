# My hardware

Mine, or that I've had access to at some point.

-   Sony Xperia
    -   Sony Xperia U ST25i. Released May 2012, stuck at Android 4.0.4. The second smartphone released by Sony, after it bought Motorola mobile.
        -   No SD card slot <http://forum.xda-developers.com/xperia-u/issues/micro-sd-card-slot-t1860365>
        -   CyanogenMod: no official image, but there is an XDA hack: <https://www.youtube.com/watch?v=jMJrLbzU2pI>
-   Recon Jet

## ThinkPad

### W540

I don't have access to this anymore.

Released 2014, given to me 2016 by from Savoir-faire Linux.

Specs: <http://shop.lenovo.com/us/en/laptops/thinkpad/w-series/w540/#tab-tech_specs>

<https://en.wikipedia.org/wiki/ThinkPad_W_Series#W540>

Camera: `v4l2-ctl --list-formats-ext` says 720p 30 FPS.

Display: 1080p 60FPS 15.6"

Graphics: NVIDIA GK107GLM [Quadro K1100M] http://silicongenesis.stanford.edu/complete_listing.html

### P710 with NVIDIA GTX 1080

### P710 with NVIDIA GTX 1080

Ubuntu 16.10:

`__GL_SYNC_TO_VBLANK=0 glxgears`: 27k FPS :-)

`glmark2`:

    =======================================================
        glmark2 2014.03+git20150611.fa71af2d
    =======================================================
        OpenGL Information
        GL_VENDOR: 	NVIDIA Corporation
        GL_RENDERER:   GeForce GTX 1080/PCIe/SSE2
        GL_VERSION:	4.5.0 NVIDIA 375.39
    =======================================================
    [build] use-vbo=false: FPS: 11541 FrameTime: 0.087 ms
    [build] use-vbo=true: FPS: 24095 FrameTime: 0.042 ms
    [texture] texture-filter=nearest: FPS: 23185 FrameTime: 0.043 ms
    [texture] texture-filter=linear: FPS: 23179 FrameTime: 0.043 ms
    [texture] texture-filter=mipmap: FPS: 23209 FrameTime: 0.043 ms
    [shading] shading=gouraud: FPS: 22256 FrameTime: 0.045 ms
    [shading] shading=blinn-phong-inf: FPS: 22304 FrameTime: 0.045 ms
    [shading] shading=phong: FPS: 21591 FrameTime: 0.046 ms
    [shading] shading=cel: FPS: 21558 FrameTime: 0.046 ms
    [bump] bump-render=high-poly: FPS: 17197 FrameTime: 0.058 ms
    [bump] bump-render=normals: FPS: 24586 FrameTime: 0.041 ms
    [bump] bump-render=height: FPS: 23935 FrameTime: 0.042 ms
    [effect2d] kernel=0,1,0;1,-4,1;0,1,0;: FPS: 20152 FrameTime: 0.050 ms
    [effect2d] kernel=1,1,1,1,1;1,1,1,1,1;1,1,1,1,1;: FPS: 15354 FrameTime: 0.065 ms
    [pulsar] light=false:quads=5:texture=false: FPS: 23693 FrameTime: 0.042 ms
    [desktop] blur-radius=5:effect=blur:passes=1:separable=true:windows=4: FPS: 7046 FrameTime: 0.142 ms
    [desktop] effect=shadow:windows=4: FPS: 9241 FrameTime: 0.108 ms
    [buffer] columns=200:interleave=false:update-dispersion=0.9:update-fraction=0.5:update-method=map: FPS: 1270 FrameTime: 0.787 ms
    [buffer] columns=200:interleave=false:update-dispersion=0.9:update-fraction=0.5:update-method=subdata: FPS: 1370 FrameTime: 0.730 ms
    [buffer] columns=200:interleave=true:update-dispersion=0.9:update-fraction=0.5:update-method=map: FPS: 1365 FrameTime: 0.733 ms
    [ideas] speed=duration: FPS: 11825 FrameTime: 0.085 ms
    [jellyfish] <default>: FPS: 17647 FrameTime: 0.057 ms
    [terrain] <default>: FPS: 1683 FrameTime: 0.594 ms
    [shadow] <default>: FPS: 17168 FrameTime: 0.058 ms
    [refract] <default>: FPS: 6382 FrameTime: 0.157 ms
    [conditionals] fragment-steps=0:vertex-steps=0: FPS: 22375 FrameTime: 0.045 ms
    [conditionals] fragment-steps=5:vertex-steps=0: FPS: 22355 FrameTime: 0.045 ms
    [conditionals] fragment-steps=0:vertex-steps=5: FPS: 22480 FrameTime: 0.044 ms
    [function] fragment-complexity=low:fragment-steps=5: FPS: 22616 FrameTime: 0.044 ms
    [function] fragment-complexity=medium:fragment-steps=5: FPS: 22500 FrameTime: 0.044 ms
    [loop] fragment-loop=false:fragment-steps=5:vertex-steps=5: FPS: 22584 FrameTime: 0.044 ms
    [loop] fragment-steps=5:fragment-uniform=false:vertex-steps=5: FPS: 22530 FrameTime: 0.044 ms
    [loop] fragment-steps=5:fragment-uniform=true:vertex-steps=5: FPS: 22352 FrameTime: 0.045 ms
    =======================================================
                                    glmark2 Score: 17352
    =======================================================

### P51

Bought: 2017.

HW specs:

- Intel Core i7-7820HQ Processor (8MB Cache, up to 3.90GHz)
- Windows 10 Pro 64
- Windows 10 Pro 64 WE (EN/FR/DE/NL/IT)
- 15.6" FHD (1920x1080), anti-glare, IPS
- 32GB(16+16) DDR4 2400MHz SODIMM
- NVIDIA Quadro M1200 4GB GDDR5
- With Color Sensor
- 720p HD Camera with Microphone
- Keyboard with Number Pad - Euro English
- 3+3BCP, Fingerprint Reader,Color Sensor
- Integrated Fingerprint Reader
- Hardware dTPM2.0 Enabled
- 1TB 5400rpm HDD
- 512GB SSD PCIe TLC OPAL2
- 1.5TB
- 170W AC Adapter - UK(3pin)
- 6 Cell Li-Polymer Battery, 90Wh
- Intel Dual Band Wireless AC(2x2) 8265, Bluetooth Version 4.1, vPro

Ubuntu 17.10 setup fun:

- partition setup: https://askubuntu.com/questions/343268/how-to-use-manual-partitioning-during-installation/976430#976430
- BIOS:
    - for NVIDIA driver: https://askubuntu.com/questions/343268/how-to-use-manual-partitioning-during-installation/976430#976430
    - for KVM, required by Android Emulator: enable virtualization extensions
- TODO fix the brightness keys:
    - failed: https://askubuntu.com/questions/769006/brightness-key-not-working-ubuntu-16-04-lts/770100#770100

Reddit threads:

- https://www.reddit.com/r/linux4noobs/comments/5zyejw/update_1604_tp_1610_boot_hangs_at_started_nvidia/
- https://www.reddit.com/r/Lenovo/comments/6g8m9w/ubuntu_on_lenovo_p51/
- https://www.reddit.com/r/thinkpad/comments/6hi0zn/if_youre_thinking_of_running_linux_on_a_p51_read/

Battery:

- before GPU: 8h
- after GPU: 6.5h

### T430

<http://shop.lenovo.com/us/en/laptops/thinkpad/t-series/t430/#tab-tech_specs>

TYPE 2344-CTO PBXGKXD 12/10

- Serial Number: 2344CTO
- Machine Type: PBXG
- Machine Type Model: PBXGKXD

Released 2012.

Graphics: NVIDIA NVS 5400M.

1600x900 max resolution.

#### Intel i5-3210M CPU

<https://ark.intel.com/products/67355/Intel-Core-i5-3210M-Processor-3M-Cache-up-to-3_10-GHz-rPGA>

Launch date: Q2'12

Price: 225 USD

TDP: 35W

2.5GHz

Cores: 2

AVX extension (4 32-bit floats).

FMA GFLOPS: 2.5 * 2 * 4 = 20

Ubuntu 16.10 `glmark2`:

    =======================================================
        glmark2 2014.03+git20150611.fa71af2d
    =======================================================
        OpenGL Information
        GL_VENDOR:     NVIDIA Corporation
        GL_RENDERER:   NVS 5400M/PCIe/SSE2
        GL_VERSION:    4.5.0 NVIDIA 375.39
    =======================================================
    [build] use-vbo=false: FPS: 2341 FrameTime: 0.427 ms
    [build] use-vbo=true: FPS: 2286 FrameTime: 0.437 ms
    [texture] texture-filter=nearest: FPS: 2146 FrameTime: 0.466 ms
    [texture] texture-filter=linear: FPS: 2261 FrameTime: 0.442 ms
    [texture] texture-filter=mipmap: FPS: 2366 FrameTime: 0.423 ms
    [shading] shading=gouraud: FPS: 2028 FrameTime: 0.493 ms
    [shading] shading=blinn-phong-inf: FPS: 1846 FrameTime: 0.542 ms
    [shading] shading=phong: FPS: 1521 FrameTime: 0.657 ms
    [shading] shading=cel: FPS: 1554 FrameTime: 0.644 ms
    [bump] bump-render=high-poly: FPS: 956 FrameTime: 1.046 ms
    [bump] bump-render=normals: FPS: 2265 FrameTime: 0.442 ms
    [bump] bump-render=height: FPS: 2228 FrameTime: 0.449 ms
    [effect2d] kernel=0,1,0;1,-4,1;0,1,0;: FPS: 1180 FrameTime: 0.847 ms
    [effect2d] kernel=1,1,1,1,1;1,1,1,1,1;1,1,1,1,1;: FPS: 504 FrameTime: 1.984 ms
    [pulsar] light=false:quads=5:texture=false: FPS: 1205 FrameTime: 0.830 ms
    [desktop] blur-radius=5:effect=blur:passes=1:separable=true:windows=4: FPS: 401 FrameTime: 2.494 ms
    [desktop] effect=shadow:windows=4: FPS: 634 FrameTime: 1.577 ms
    [buffer] columns=200:interleave=false:update-dispersion=0.9:update-fraction=0.5:update-method=map: FPS: 464 FrameTime: 2.155 ms
    [buffer] columns=200:interleave=false:update-dispersion=0.9:update-fraction=0.5:update-method=subdata: FPS: 709 FrameTime: 1.410 ms
    [buffer] columns=200:interleave=true:update-dispersion=0.9:update-fraction=0.5:update-method=map: FPS: 685 FrameTime: 1.460 ms
    [ideas] speed=duration: FPS: 1336 FrameTime: 0.749 ms
    [jellyfish] <default>: FPS: 605 FrameTime: 1.653 ms
    [terrain] <default>: FPS: 64 FrameTime: 15.625 ms
    [shadow] <default>: FPS: 745 FrameTime: 1.342 ms
    [refract] <default>: FPS: 199 FrameTime: 5.025 ms
    [conditionals] fragment-steps=0:vertex-steps=0: FPS: 1065 FrameTime: 0.939 ms
    [conditionals] fragment-steps=5:vertex-steps=0: FPS: 769 FrameTime: 1.300 ms
    [conditionals] fragment-steps=0:vertex-steps=5: FPS: 1168 FrameTime: 0.856 ms
    [function] fragment-complexity=low:fragment-steps=5: FPS: 1196 FrameTime: 0.836 ms
    [function] fragment-complexity=medium:fragment-steps=5: FPS: 1080 FrameTime: 0.926 ms
    [loop] fragment-loop=false:fragment-steps=5:vertex-steps=5: FPS: 1216 FrameTime: 0.822 ms
    [loop] fragment-steps=5:fragment-uniform=false:vertex-steps=5: FPS: 1172 FrameTime: 0.853 ms
    [loop] fragment-steps=5:fragment-uniform=true:vertex-steps=5: FPS: 1077 FrameTime: 0.929 ms
    =======================================================
                                    glmark2 Score: 1250 
    =======================================================

### T400

Thrown out: 2017

Sometimes it does not turn on.

TYPE 2764-CTO S/N R8-07DF 10/03

<https://support.lenovo.com/us/en/find-product-name> says:

- Serial Number: R807DF
- Machine Type: 2668
- Machine Type Model: 2668KHU

#### NVIDIA NVS 310 GPU

Release date: 2012

Price: 130 dollars.

GFLOPS: TODO.

#### Intel Xeon E5-1660 v3 CPU

<https://ark.intel.com/products/82766/Intel-Xeon-Processor-E5-1660-v3-20M-Cache-3_00-GHz>

Price: 1000 dollars.

TDP: 140 W

Release date: Q3'14

3.0GHz

Cores: 16

AVX2 extension (8 32-bit floats).

FMA GFLOPS: 3.0 * 16 * 8 = 384

## Sony Xperia

### Z3 D6643

Specs:

- <http://www.sonymobile.com/us/products/phones/xperia-z3/#specifications>
- <http://www.gsmarena.com/sony_xperia_z3-6539.php>

Display: 5.2" FHD 1080p (1920x1080) TODO 60FPS?

Carrier: Vivo.

Camera:

- video: 2160p@30fps, 1080p@60fps, 720p@120fps, HDR, check quality

Released 2015, bought dec 2015 in Brazil.

Brazil only model it seems, <http://forum.xda-developers.com/z3/help/how-to-proceed-d6643-model-t2960099>, but very similar to the more international D6653.

Battery removal is non trivial if you have no experience: <https://www.youtube.com/watch?v=lKkqT5nF7Yw> Requires the sucking 

Service menu review: <https://www.youtube.com/watch?v=msHrHeLX1Ok>

SoC: Qualcomm MSM8974AC Snapdragon 801, Quad-core 2.5GHz, 64-bit.

CPU: Krait 400 <https://en.wikipedia.org/wiki/Krait_%28CPU%29> ARMv7-A architecture custom core (architecture license).

GPU: Adreno 330

2018: I think the SD card got pulled out, then:

- it takes a while for display to show up after phone sleeps (power button, and wait a few minutes. Immediate wakeup works, it must enter some sleep mode afterwards)
- there are random flickers / static after it comes back, or when some actions come up:
    - <https://www.youtube.com/watch?v=y-BYsu1h7RA>
    - <https://www.youtube.com/watch?v=9LBR9cGs_xs>
    - <https://talk.sonymobile.com/t5/Xperia-Z2/Colored-Lines-on-Screen-and-Flickering/td-p/1096112>

I removed SD card, and did factory reset, but nothing.

Safe mode: hold power button, then hold power off on screen, then it asks you. Disables all third party apps (non-pre installed).

Tried opening it, it was hard, all glued crap. Managed, but could see nothing wrong with display cable.

### L1 G3311

Bought: 2017.

<https://www.gsmarena.com/sony_xperia_l1-8619.php>

## Logitech C920 webcam

Savoir-faire Linux, given to me 2016.

Specs:

- <http://business.logitech.com/en-us/product/c920-hd-pro-webcam-business>
- <http://www.logitech.com/en-us/product/hd-pro-webcam-c920>

Exact part number: PN 960-000764

1080p, 30FPS

H.264 encoding on board

Implements the <https://en.wikipedia.org/wiki/USB_video_device_class> standard, which has an implementation on the Linux kernel.

## Keyboard

### Kinesis Advantage 2

Serial: 45470A2

Buy date: 2018-04-10

Supplier: Osmond Group Limited

## Motorola 6G

https://www.gsmarena.com/motorola_moto_g6-9000.php

Bought: 2018

## Logitech k400r wireless keyboard

Bought: 2015

Disable horrible Fn key behaviour: <http://askubuntu.com/questions/170819/how-to-program-logitech-function-keys> 

Some other k models can configure hardware directly: <http://www.logitech.com/en-us/manuals/k380-setup-guide>

## Logitech k400r wireless keyboard

## Washing machine

Laden EV1049

The filter is very small: https://www.youtube.com/watch?v=NQquRaHuGLw

## Orange Pi PC

<http://www.orangepi.org/orangepipc/>

Board LED does not turn on (turned on on first plug, Ethernet always turns on):

- <http://www.orangepi.org/orangepibbsen/forum.php?mod=viewthread&tid=470>
- <https://www.youtube.com/watch?v=ZtUn-dnJFdU> says only one specific supply worked..
- <https://www.reddit.com/r/raspberry_pi/comments/3jamn1/any_orange_pi_owners_here_help_with_power_imput/> Comment <https://www.reddit.com/r/raspberry_pi/comments/3jamn1/any_orange_pi_owners_here_help_with_power_imput/cy79a7w> says it only worked with the official supply...

Now just HDMI does not work. Possibly a monitor vs television problem:

- <http://www.orangepi.org/orangepibbsen/forum.php?mod=viewthread&tid=475>

## TTL to USB

- https://web.archive.org/web/20160903121838/http://www.ebay.co.uk/itm/CP2102-Micro-USB-to-UART-TTL-Serial-Adapter-3-3V-5V-6Pin-for-ESP8266-Arduino-Pi-/181919478543 idVendor=10c4  idProduct=ea60

## Raspberry Pi

### Raspberry Pi 2

Model B V 1.1.

SoC: BMC2836

<https://www.raspberrypi.org/products/raspberry-pi-2-model-b/>

### Raspberry Pi 3

Model B V 1.2.

SoC: BCM2837

## BBC Micro Bit

<https://en.wikipedia.org/wiki/Micro_Bit>

## Internet speed

Home 2017/08 TalkTalk 38Mbps nominal, Google M-lab speed test:

- 36.4 Mbps download
- 9.15 Mbps up
- 58 ms latency over 80km of first world

## Kindle

Kindle D01100
