# ColorBerry
This is for ColorBerry, which is available on [discord](https://discord.gg/2uGPpVmCCE) and [Elecrow](https://www.elecrow.com/colorberrywithmetalcase.html)

# Main feature
* New Charging IC: Enjoy faster charging with a new IC that supports up to 1A (origin beepy is 100mA).
* Efficient Power Consumption: The same power consumption as a Sharp black-and-white screen when the backlight is off. (Yes, we have a backlight!)
* Vibrant Display: A 3-bit, 8-color screen with a dithering driver for smooth visuals.
* Battery : 5000mAh: Battery life to 20 hours with raspberry zero 2w, and 10 hours with orangepi zero 2w.
* Ready to Go:Everything is pre-configured and works out of the box,no long waits! We hate delays as much as you do. Built in small batches in China,and shipment starts within a week.
* size:5000mah: 73mm 104mm 17mm 180g
* Case : CNC metal case, with better heat dissipation.
* Board Options:
   * Orange pi zero 2W with 4GB RAM
   * Raspberry pi zero 2W with 512M RAM
# How to Order
  * Message me @alex in [discord](https://discord.gg/2uGPpVmCCE) to place your order. Accept Alipay.
  * Elecrow. Accept Paypal.
      * Metal case:  [Elecrow](https://www.elecrow.com/colorberrywithmetalcase.html)
      * Metal case only:  [Elecrow](https://www.elecrow.com/metalcaseforcolorberry.html)
# Driver
* [jdi screen driver and configure file](https://github.com/hyphenlee/jdi-drm-rpi)
* [orangepi keyboard driver](https://github.com/hyphenlee/beepy-kbd-orangepi)
* [origin keyboard driver for raspberry pi](https://github.com/ardangelo/beepberry-keyboard-driver)

# default username
## raspberry pi
username: hyphen  
password: hyphen
## orangepi
username: orangepi  
password: orangepi
# default commmand 
all these commands is aliases in `~/.zshrc`
## screen dithering commands
`d0` : close screen dithering  
`d3` : default screen dithering  
`d4` : max dithering , best for image display  
you can change default setting in /etc/rc.local  

## backlight commands
`b` : turn on backlight  
`bn` ：close backlight  
or control by side button
## touch pad commands：
`key` ： use touch pad as arrow key  
`mouse` ： use touch pad as mouse

## desktop（experimental ):
raspberry pi: ` su -l hyphen -c xinit`   
orangepi: ` su -l orangepi -c xinit`  
# keymap
## [origin beepy keymap on cli](https://github.com/ardangelo/beepberry-keyboard-driver/tree/main?tab=readme-ov-file#basic-key-mappings)
## [keymap on desktop](https://github.com/hyphenlee/jdi-drm-rpi?tab=readme-ov-file#keyboard-input-under-gui)
