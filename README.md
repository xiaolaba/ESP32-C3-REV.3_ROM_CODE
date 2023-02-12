### ESP32-C3-REV.3_ROM_CODE

dump and try to understand the ROM code  
download  

https://www.esp32.com/viewtopic.php?t=21331 https://dl.espressif.com/dl/esp32c3_rev3_rom.elf  
elf parser

http://www.sunshine2k.de/coding/javascript/onlineelfviewer/onlineelfviewer.html  
https://github.com/horsicq/XELFViewer/releases  


partial info, complete text see [esp32c3_rev3_rom_elf.txt](esp32c3_rev3_rom_elf.txt)
```
Result:
ELF header
==========

Name           Offset         NumValue            Value          
EI_MAG:        0x00000000     0x7F454C46          �ELF
EI_CLASS       0x00000004     0x01                32 BIT
EI_DATA        0x00000005     0x01                DATA2LSB (Little-Endian)
EI_VERSION     0x00000006     0x01                EV_CURRENT
EI_OSABI       0x00000007     0x00                UNIX System V ABI
EI_OSABIVER    0x00000008     0x00                
E_TYPE         0x00000010     0x0002              ET_EXEC (Executable file)
E_MACHINE      0x00000012     0x00F3              Unknown
E_VERSION      0x00000014     0x00000001          EV_CURRENT
E_ENTRY        0x00000018     0x40000000          
E_PHOFF        0x0000001C     0x00000034          
E_SHOFF        0x00000020     0x011ED8BC          
E_FLAGS        0x00000024     0x00000001          
E_EHSIZE       0x00000028     0x0034              
E_PHENTSIZE    0x0000002A     0x0020              
E_PHNUM        0x0000002C     0x001C              
E_SHENTSIZE    0x0000002E     0x0028              
E_SHNUM        0x00000030     0x004B              
E_SHSTRNDX     0x00000032     0x004A              
```