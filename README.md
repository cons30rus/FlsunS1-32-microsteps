# FlsunS1-32-microsteps
Flsun S1 motor driver board firmware to enable 32 microsteps

I made this firmware for Flsun S1 motor driver board to change its logic to 32 microsteps instead 16 microsteps in original Flsun S1 firmware. 
It was made on base official Flsun motor_v2.0.3.bin firmware.

For this you need stm32 flasher ST-LINK, printed Closed_Loop_Boards_Tool, wiring according official Flsun procedure.
Don't forget to change microsteps parameters for all 3 motors in printer.cfg and Save&Restart after.

![Printer cfg correction](https://github.com/user-attachments/assets/ba21eb8d-0510-45d3-9e1d-93b32a7558b6)
