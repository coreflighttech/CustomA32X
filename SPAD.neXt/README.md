CORE FLIGHT TECHONOLOGIES COMPACT A32X OVERHEAD V2 PANEL firmware for SPAD.neXt SERIAL V2

# r01 Initial release (2026/04/04)

[CFT_A32X_OVH_COMPACT_SPAD_1L2P_R01_115200.ino.hex](https://github.com/coreflighttech/CustomA32X/blob/main/SPAD.neXt/CFT_A32X_OVH_COMPACT_SPAD_1L2P_R01_115200.ino.hex)

# How to install the firmware

-> https://github.com/coreflighttech/Uploader  
- Select "A32X Compact OVH" in XLoader "Device" pull down list (or MCP/FCU as it is also an ATmega2560).
- Be sure to plug the external power supply of the overhead.
- Use powered USB hub or free mothernoard USB port.

# How to use

Serial COM port has to be set to 115200 bauds in SPAD serial device settings (default bitrate)

SPAD should automaticaly load the overhead user interface from SPAD on-line database.

Internal devices features
 - Decrease digits displays brightness by pressing "CALLS ALL" and fire "ENG 1 TEST" buttons
 - Increase digits displays brightness by pressing "CALLS ALL" and fire "ENG 2 TEST" buttons
 - Display firmware version by pressing "CALLS ALL" and "APU TEST" button

To manage brightness from SPAD, use:
 - DISPLAY_BRI : Displays brightness from 0 to 255 (DEVICE:1L2P/CFTA32XOVHCOMPACTV2/DISPLAY_BRI)

SPAD test snippet for FlyByWire A32NX is #16541\
SPAD test snippet for Fenix A320 is #16548


# Firmware history

Warning, do not use <i>old_sketch_A32X_OVH_COMPACT_SPAD_1L2P_BETA02_115200.ino.hex</i> and <i>old_sketch_A32X_OVH_COMPACT_SPAD_1L2P_BETA04_115200.ino.hex</i> as they were for V1 version of the COMPACT A32X OVERHEAD.
