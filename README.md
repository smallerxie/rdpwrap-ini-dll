# About this repository "smallerxie/rdpwrap-ini"
This repository is amied to offer the WORKING "rdpwrap.ini" patch files after testing by myself.
The repository also offers the "termsrv.dll" file backup by myself on my Win10x64. If you cannot use rdpwrap after Windows Update, you may try to rollback to an earlier version of "termsrv.dll" as a secondary choice.

# How to replace your "rdpwrap.ini" file
1. Open CMD window with Administrator's right; 
2. `net stop termservice`; 
3. Copy the new "rdpwrap.ini" file to *%ProgramFiles%\RDP Wrapper* folder; 
4. `net start termservice`; 
5. If the above service(s) cannot restart, please reboot your windows. You can also, in CMD window, **cd** (ChangeDir) to the "RDPWrap-v1.6.2" folder and run **`RDPWInst -r`** as Administrator to restart the service(s).

# How to use rdpwrap
The official Github repository was closed by some reasons. Please use the backup package "RDPWrap-v1.6.2.zip" in my repository.

## Files in "RDPWrap-v1.6.2" package:

File name|Description
---|---
RDPWInst.exe | RDP Wrapper Library installer/uninstaller
RDPCheck.exe | Local RDP Checker (you can check the RDP is working)
RDPConf.exe | RDP Wrapper Configuration
install.bat | Quick install batch file (run it as administrator)
uninstall.bat | Quick uninstall batch file (run it as administrator)
update.bat | Quick update batch file (run it as administrator)

# Links:
- Official GitHub repository for rdpwrap (might be closed):
https://github.com/stascorp/rdpwrap/
- Official Telegram chat:
https://t.me/rdpwrap
- asmtron's RDP Wrapper & Autoupdate: 
https://github.com/asmtron/rdpwrap
- affinityv's repository INI-RDPWRAP: 
https://github.com/affinityv/INI-RDPWRAP
