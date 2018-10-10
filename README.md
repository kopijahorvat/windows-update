Trebat će vam Windows 7 Professional SP1 ISO, kojeg  nije moguće skinuti direktno od Microsofta bez aktivacijskog key-a. 
Srećom možete ga skinuti uz pomoć ovog programćića koji skida direktno s MS servera i ne zahtijeva admin privilegije https://www.heidoc.net/joomla/technology-science/microsoft/67-microsoft-windows-iso-download-tool 
Trebat će vam Windows Loader by Daz, skinite ga ovdje https://drive.google.com/file/d/1OigAwy3b9Zig1LgQ2zrBimr3J_xXLQjl/view?usp=sharing password je "kopijahorvat". Neki antivirus programi će se požaliti da su pronašli nešto zločesto. Preostaje vam vjera, ufanje, ljubav u mene koji vam garantira da je to false positive. Ako nemate vjere provjerite sa VirusTotalom i sve će vam biti jasno.
Spržite ISO na stick sa Rufus-om https://rufus.akeo.ie (svakako izaberite "MBR" pod "Partition scheme" izbornikom).
Ako imate noviju matičnu sa UEFI BIOS-om, u boot izborniku izaberite bootanje sa sticka koji je izlistan bez "UEFI" opcije ili jednostavno  isključite "UEFI" i uključite "Legacy/CMS" boot opciju u BIOS-u (jerbo UEFI boot ne podržava "legacy" MBR particije). Također uključite "AHCI" SATA mode.

*Ako imate računalo novije generacije (bez USB2 portova) moguće je da će vam instalacija zapeti jer W7 ISO nema integrirane USB3 drivere. U tom slučaju 
 skinite ovaj programćić:
 http://gigabytedaily.blogspot.com/2015/09/having-trouble-installing-windows-7-by.html 
 Alternativno MSI alatka služi istoj svrsi: https://forum-en.msi.com/index.php?topic=261560.0
 Oba programa NE RADE s verzijama koje prilikom instalacije nude izbor Home/Pro, 64/32-bit ili slično. ISO mora biti "single edition" verzija.

Napravite clean install W7, aktivirajte ga sa Windows Loaderom, restartajte i provjerite uz pomoć Loadera da li je aktiviran.
(Ukoliko imate problema s aktivacijom uz pomoć Loadera, pročitajte dokumentaciju koja dolazi s njime)
Skinite Microsoftov W10  Media Creation Tool, spržite ga na stick, startajte "setup.exe" i izaberite "upgrade" opciju.
Windowsi će se automatski napraviti update na verziju identičnu postojećoj verziji W7 (Home/Pro, 64/32-bit).
Nakon što se W10 instalira, spojite se na internet, stisnite Win tipku na tipkovnici, utipkajte "activation" i uz pomoć "Activation" aplikacije provjerite da li ste dobili digitalnu licencu.
Ukoliko želite koristiti UEFI boot, uključite ga u BIOSU.
Pri svakoj sljedećoj instalaciji Windosa 10 na to računalo, morate izabrati identičnu verziju (Home/Pro, 64/32-bit) da bi digitalna aktivacija proradila.
Možete mijenjati sav hardver osim matične ploče jer je digitalna licenca vezana uz nju. Kad promjenite matičnu morate cijelu proceduru od broja 1. ponoviti.
