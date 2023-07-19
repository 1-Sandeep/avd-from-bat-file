
@REM BAT Script to open android virtual device 

@REM Author: Sandeep Poudel
@echo off


@REM Path to your emulator
cd C:\Users\your_username\AppData\Local\Android\Sdk\emulator

title Open Android Virtual Device

@REM Open emulator
emulator -avd device_name
```

@REM if you do not know which avd is installed, below command will listout all avd's on your system
emulator -list-avds


