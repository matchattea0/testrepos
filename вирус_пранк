@echo off
title Critical System Error
color 0c
mode con cols=80 lines=25
powershell -windowstyle maximized -command "cmd /c"

:: 
mshta vbscript:Execute("msgbox ""CRITICAL ERROR: 0xc00000DEAD"",4096,""Windows Defender"":close")

echo.
echo [INFO] Deleting system32...
ping localhost -n 2 >nul
echo [INFO] Encrypting user data...
ping localhost -n 2 >nul
echo [INFO] Sending passwords to server...
ping localhost -n 2 >nul

:loop
echo.
echo [WARNING] Remote access detected from IP: %random%.%random%.%random%.%random%
echo [FIREWALL] Blocking port %random%...
echo [ROOTKIT] Installing trojan_%random%.exe...
ping localhost -n 1 >nul

::
color 0c
ping localhost -n 1 >nul
color 0a
ping localhost -n 1 >nul
color 0e
ping localhost -n 1 >nul
color 0c

goto loop
