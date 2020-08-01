# GPD_UDL
A Notepad++ UDL (User Defined Language) for GPD (Generic Printer Description) and GDL (Generic Description Language).

Notepad++ supports around 80 programming languages for syntax highlighting & folding, but unfortunately, most widely used GPD/GDL for PCL driver and PPD for PS driver are not supported so far by notepad++. Hence, this UDL server the purpose for GPD/GDL.

GPD: https://docs.microsoft.com/en-us/windows-hardware/drivers/print/introduction-to-gpd-files

GDL: https://docs.microsoft.com/en-us/windows-hardware/drivers/print/generic-description-language


## How it works:

It has to follow Notepad++ guideline which is intended to change time to time. For now, you have to manually install a new User Defined Language.

1. Download GPD.xml.
2. Import the file by placing the file in your userDefineLangs folder and restarting Notepad++. Alternatively, you can use the User Defined Language dialog box to Import your file, but that places the UDL in the combined file, which is more complicated to maintain. More details of what those steps entail can be found in the ["Import a UDL"](https://npp-user-manual.org/docs/user-defined-language-system/#import-a-udl) section of the official documentation.
