```bat
@echo off
:start
YOUR\PATH\Program.exe
:: TIMEOUT /T 30
:: pause
goto start
```


```bat
TIMEOUT /T 30
```
Means the program will wait 30 seconds before relaunching your exe


```bat
pause
```
Means ou will need to press any key to relaunch your exe
