STM32 Projects implementing external libs
(open subdirectories for project images and details)

# [1) Laptop Battery Monitor](./USB_COM)

After recommissioning an old laptop to use as a server, I set out to create a physical display to display generic numerical data to be used in conjunction with scripts and programs. Data is send via USB using existing COM port libraries. Scripts should echo raw numerical data directly to the STM32 serial ports.

-- TO USE: 
1) flash .elf file inside build
2) connect stm32 via usb
3) run STbat.sh ( in Scripts ) 
---

## *breadboard prototype*
![image](./USB_COM/Prototype.jpg)

*LCD wiring(for stm32f103 dev board)*
![image](./USB_COM/segment_display.png)
