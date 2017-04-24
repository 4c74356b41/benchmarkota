Invoke-WebRequest https://tryh4rder.blob.core.windows.net/crapito/CrystalDiskMark5_2_1.zip -OutFile crystal.zip
Invoke-WebRequest https://tryh4rder.blob.core.windows.net/crapito/Geekbench-4.1.0-WindowsSetup.exe -OutFile geekbench.exe
Invoke-WebRequest https://tryh4rder.blob.core.windows.net/crapito/novabench.exe -OutFile novabench.exe
Invoke-WebRequest https://tryh4rder.blob.core.windows.net/crapito/Unigine_Heaven-4.0.exe -OutFile heaven.exe

Multi Seq: -b128K -d5 -oQQQ -tTTT -W -S -wWWW
Multi 4K: -b4K -d5 -oQQQ -tTTT -W -r -S -wWWW
Single Seq: -b1M -d5 -o1 -t1 -W -S -wWWW
Single 4K: -b4K -d5 -o1 -t1 -W -r -S -wWWW

Google  - n4        europe-west1-b  SSD100GB
Azure   - ds3_v2    westeurope      default
AWS     - 

