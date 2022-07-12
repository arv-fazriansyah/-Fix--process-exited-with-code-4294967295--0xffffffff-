# [Fix] The system cannot find the file specified [process exited with code 4294967295 (0xffffffff)]
Fix WSL2 Ubuntu 20.4 Terminal Windows.
The system cannot find the file specified.
[process exited with code 4294967295 (0xffffffff)]

Change Command Line:
C:\Windows\system32\wsl.exe -d Ubuntu

Change To:
%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe ubuntu

Done :)

