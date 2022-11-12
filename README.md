# **_SnoF's_ Troubleshooting Repository**
# **[Facebook](https://www.facebook.com/snof69)   [Instagram](https://www.instagram.com/snof.gg)   [Discord Server](https://discord.gg/EUATtbzP)**


Issue: There is no VBIOS support detected in this card. 'BIOS CSM/UEFI Mode' settings in BIOS will be change to 'UEFI'.
>Solution 1: Try plugging your ***Display Interface*** cable to your GPU and turn on your PC, and then remove all cables connected to your PC and open side panel and remove CMOS battery, wait for a few minutes and then put the CMOS battery back in and plug everything and try turning it again.


Issue: BLUE SCREEN OF DEATH (BSOD)
>Solution: Any problems related to BSOD can be tracked down easily by using [WinDBG <sub>Download</sub>](https://apps.microsoft.com/store/detail/windbg-preview/9PGJGD53TN86) 
>Open WinDBG as administrator and open dump file which is located here <"C:\Windows\Minidump\"> and click on analyze -v and wait for WinDBG to check the file. Once it's done, scroll down until you find BUGCHECK Code. You can search the BUGCHECK Code on Google to find out what is causing the BSODs.


Issue: 
> Solution:

[Contribution: Mostafa Al Faysal](CONTRIBUTING.md)
