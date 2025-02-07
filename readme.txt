Example for the Programming Flow:
@Note the first step "-C 1" and the last step "-C 0" is necessary!

C:\>NuLink_1T8051 -C 1
C:\>NuLink_1T8051 -R CHIPINFO
C:\>NuLink_1T8051 -E SPROM
C:\>NuLink_1T8051 -W SPROM C:\SPROM.bin
C:\>NuLink_1T8051 -V SPROM C:\SPROM.bin
C:\>NuLink_1T8051 -A
C:\>NuLink_1T8051 -E ALL
C:\>NuLink_1T8051 -W CFG 0xFD 0xFD 0xFF 0xFF 0xFF
C:\>NuLink_1T8051 -W APROM C:\APROM.bin
C:\>NuLink_1T8051 -W APROM C:\DATA.bin 0x1000
C:\>NuLink_1T8051 -W LDROM C:\LDROM.bin
C:\>NuLink_1T8051 -C 0
