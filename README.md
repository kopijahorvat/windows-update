Trebat će vam W7 SP1 RTM ISO (Home/Pro), kojeg  nije moguće skinuti direktno od Microsofta bez aktivacijskog key-a. 
Srećom možete ga skinuti uz pomoć ovog programćića koji skida direktno s MS servera i ne zahtijeva admin privilegije https://www.heidoc.net/joomla/technology-science/microsoft/67-microsoft-windows-iso-download-tool 
Alternativni link: https://drive.google.com/file/d/1fkCm3MW4FJ9G1e6RPctJ0xbWS_kBilIa/view?usp=sharing (provjeren VirusTotal-om)
Također možete skinuti .torrent file i provjeriti hash kako je objašnjeno ovdje https://www.pcsteps.com/45-download-windows-7-iso-legally-free-digital-river/
Trebat će vam Windows Loader by Daz, skinite ga ovdje https://drive.google.com/file/d/1OigAwy3b9Zig1LgQ2zrBimr3J_xXLQjl/view?usp=sharing password je "kopijahorvat". Neki antivirus programi će se požaliti da su pronašli nešto zločesto. Preostaje vam vjera, ufanje, ljubav u mene koji vam garantira da je to false positive. Ako nemate vjere provjerite sa VirusTotalom i sve će vam biti jasno.
Spržite W7 ISO na stick sa Rufusom i svakako izaberite "MBR partition scheme for BIOS/UEFI" pod "Partition scheme" izbornikom.
Iskopčajte LAN kabel na računalu.
Isključite "UEFI boot opciju" u BIOS-u jerbo Windows Loader šljaka samo u "legacy" boot modu. Također uključite "AHCI" SATA mode.
Napravite clean install W7, aktivirajte ga sa Windows Loaderom, restartajte, provjerite da li je aktiviran uz pomoć Windows Loadera.
(Ukoliko imate problema s aktivacijom uz pomoć Loadera, pročitajte dokumentaciju koja dolazi s njime)
Skinite Microsoftov W10  Media Creation Tool, spržite ga na stick, startajte "setup.exe" i izaberite "upgrade" opciju.
Windowsi će se automatski napraviti update na verziju identičnu postojećoj verziji W7 (Home/Pro, 64/32-bit).
Nakon što se W10 instalira, spojite se na internet, stisnite Win tipku na tipkovnici, utipkajte "activation" i uz pomoć "Activation" aplikacije provjerite da li ste dobili digitalnu licencu.
Ukoliko želite koristiti UEFI boot, uključite ga u BIOSU.
Pri svakoj sljedećoj instalaciji Windosa 10 na to računalo, morate izabrati identičnu verziju (Home/Pro, 64/32-bit) da bi digitalna aktivacija proradila.
Možete mijenjati sav hardver osim matične ploče jer je digitalna licenca vezana uz nju. Kad promjenite matičnu morate cijelu proceduru od broja 1. ponoviti.
