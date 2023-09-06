# Razer Battery Taskbar
Original from https://github.com/Tekk-Know/RazerBatteryTaskbar  
forked from https://github.com/KaomN/RazerBatteryTaskbar

Modified to Support Basilisk V3 Pro (Wireless, Plugged in).

![image](https://github.com/Gucioo/RazerBatteryTaskbar/assets/7483436/35573b69-bfe5-4e20-ae93-59de1e3ee45f)


# Windows Compile Instructions

Google and download:

install node.js

install git

==============================================================================

copy GIT archive to C:\Electron\RazerBatteryTaskbar

cd C:\Electron\RazerBatteryTaskbar


npm install --save-dev @electron-forge/cli

npm exec --package=@electron-forge/cli -c "electron-forge import"


npm audit fix


===============================================================================


npm exec --package=@electron-forge/cli -c "electron-forge make"

  › Artifacts available at: C:\Electron\RazerBatteryTaskbar\out\make

Make sure there is 1GB free space on HDD for succesfull compile.


![image](https://github.com/Gucioo/RazerBatteryTaskbar/assets/7483436/b45f7ed3-be59-4d7e-a970-642372a3c559)

