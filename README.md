# Startup-file-and-linker-script-for-ARM-cortex-m4-microcontroller-STM32L433RC

START-UP FILE IS THE FIRST PROGRAM THAT GETS EXECUTED IN A MICROCONTROLLER. IT DEFINES THE VECTOR TABLE OF THE MICROCONTROLLER AND CONTAINS THE RESET HANDLER. THE RESET HANDLER IS THE FUNCTION THAT GETS EXECUTED AFTER A RESET OF THE MICROCONTROLLER. THE RESET HANDLER DOES CERTAIN INITIALIZATION LIKE MOVING THE .data SECTION FORM THE FLASH MEMORY TO THE SRAM AND INITIALIZING THE .bss SECTION WITH ALL ZEROS AND THEN FINALLY CALLS THE MAIN() FUNCTION OF THE USER PROGRAM.

THE LINKER SCRIPT IS THE ONE THAT LINKS ALL THE DIFFERENT USER FILES OF A USER PROGRAM AND MAKES IT INTO A SINGLE FINAL EXECUTABLE FILE. IT MERGES ALL THE DIFFERENT SECTIONS OF THE FILES TOGETHER AND ASSIGNS THE ABSOLUTE ADDRESS OF THE PROCESSOR CODE AND DATA MEMORY TO IT.
