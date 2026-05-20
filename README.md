installing:
right click on audientusbaudio.inf -> install
and 
right click on audientusbaudioks.inf -> install

copy Audient folder to C:\Program Files

open cmd as Admin and run: C:\Windows\System32\regsvr32.exe "C:\Program Files\Audient\USBAudioDriver\x64\audientusbaudioasio_x64.dll"

import audient_registry_fix.reg to enable ASIO buffer size control in the Audient iD tray application

<img width="305" height="189" alt="Screen-111" src="https://github.com/user-attachments/assets/838f0d02-5555-4797-9470-0ebcfe03473b" />
<img width="662" height="649" alt="Screen-112" src="https://github.com/user-attachments/assets/903788cd-89d4-486a-ab7e-5f1ab53e1fac" />
