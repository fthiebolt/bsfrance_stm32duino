# bsfrance_stm32duino
stm32duino support for BSFrance stm32l151c8t6 board featuring a sx1276 (LoRa) module

https://bsfrance.fr/lora-long-range/1368-LoRaM3-D-L151-LoRa-STM32-OLED-LiPo-development-board-long-range-ARM-SX1276.html

### Howto
Just run script './deploy.sh' and board will get added to your Arduino boards list

Please note that i don't use BSFrance's USB bootloader ... instead i prefer the serial one embedded within each stm32 :)
For such behaviour, you just need to switch a selector.

### TODO
a lot ... for example nothing was done to provide USB support ...

Ultimately, my goal is to get rid of this repository and to have thoses boards* supported within stm32duino toolchain :)

* STM32L151C8T6, STM32F103 & STM32F303
