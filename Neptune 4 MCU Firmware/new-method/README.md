# How to Dump/Flash Neptune 4 MCU Firmware

**Warning:** Only flash this firmware on a DE-ELEGOO setup/image, **not** on stock Elegoo software.

## Steps:

1. **Solder/Wire bridge the following two sets of jumper pads (with machine off):**\
![Alt text](/pictures/pads-bridge.jpg)

3. **Run SoftwareFlash Install Script then reboot:**

   ```
   ./mcu-swflash-install.sh
   ```

4. **Run SoftwareFlash Script with the following options (be sure to press , Q , then select "yes" when done):**

   ```
   ./mcu-swflash-run.sh
   ```
      
![Alt text](/pictures/flash.png)




