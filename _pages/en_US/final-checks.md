---
title: "Final checks"
---

{% include toc title="Table of Contents" %}

### Checking the STM32 bootloader

We are going to see if the STM32 bootloader is effectively unlocked:
1. Power off the calculator
2. Press and hold 6
3. Press the reset button at the back of the device

If the LED turns red and the screen stays black, everything is fine. You can release 6 and press reset again to go back in the firmware.

If it's not the case, please join the [Omega Discord](https://discord.gg/X2TWhh9) and ask for help.
{: .notice--warning}


### GG!

Well done, you are now the proud owner of an unlocked Numworks. You can now do whatever you want with the hardware you bought
with your own money. If you want, you can join the [Omega Discord](https://discord.gg/X2TWhh9) to say hello.

### Mode informations about Phi

If you have installed the Phi bootloader, here is some piece of info you might need.

- You can access the STM32 DFU bootloader (called "hwloader") by holding 6 while pressing reset.
- You can access Phi's DFU bootloader (called "softloader") by holding 4 while pressing reset.

___

If you want to use install Epsilon with the new bootloader, continue to [Install Epsilon from softloader](install-epsilon-from-softloader)
{: .notice--info}
