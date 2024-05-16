# 27C0x1_EMU
Emulator for the 27C011/27C513 EPROM<br>
This is an interposer/adapter to allow standard EPROM or FLASH devices to be used where a hard-to-find (and harder-to-program) bank-switched EPROM is required (such as the 27C513 or 27C011).<br>
WRT the end use product, it is form-fit-function replacement for the 27C513/27C011 devices.<br>
Provision is made to accomodate up to a 4Mb device (bank-switching A14 thru A19).  Also, the 25C513 emulator can be configured with 0-ohm resistors<br>
Generally, the base device must be programmed separately, then installed in the emulator.  5V FLASH devices may be programmable in the emulator if the programming device can accomodate the galgorithm and bank-switching (not likely unless you are rolling your own).<br>
Maximum bus speed is approximately 2MHz and is limited by the response of the bank latch and the memory device.
