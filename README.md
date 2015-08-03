# uClinux_bfin
=========================

Installing and pushign uBoot image:

Push the file u-boot-bf609-ezkit-spi-2012R2-RC3.ldr using the ICE-100 debugger and cces tool. Use the command:

cldp.exe -proc ADSP-BF609 -emu 100b -driver bf609_w25q32bv_dpia.dxe -cmd info -cmd prog -erase all -format bin -offset 0 -format bin -offset 0 -file u-boot-bf609-ezkit-spi-2012R2-RC3.ldr
