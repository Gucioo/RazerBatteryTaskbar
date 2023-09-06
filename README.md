# Razer Battery Taskbar
Original from https://github.com/Tekk-Know/RazerBatteryTaskbar  
forked from https://github.com/KaomN/RazerBatteryTaskbar

Modified to Support Basilisk V3 Pro (Wireless, Plugged in).

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
