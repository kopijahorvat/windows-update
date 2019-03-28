
           Doljenavedena procedura omogućit će vam da besplatno aktivirate Windows 10 putem digitalne licence

Najjednostavnije je da W10 aktivirate uz pomoć HWIDGEN aktivatora kojeg skinete ovdje: https://www.reddit.com/r/piracy/wiki/tools
HWIDGEN većina antivirusa prepoznaje kao virus/trojan jer modificira registry, no ako ga skinete sa "službenih" stranica https://www.nsaneforums.com/topic/312871-windows-10-digital-license-hwid-kms38%E2%84%A2-generation/ nema razloga za brigu. 

Malo kompliciranija metoda je slijedeća:
Trebat će vam Windows 7 PRO SP1 ISO, kojeg  nije moguće skinuti direktno od Microsofta bez aktivacijskog key-a. 
Skinite ga sa mojeg Google Drive-a https://drive.google.com/file/d/18-6Nsccs_HA8W2C25_JMnMXMl3XmQKS3
Ako ste paranoidni usporedite SHA1 vrijednosti uz pomoć ove liste: http://naterice.com/windows-7-and-7-1-iso-names-and-sha1-hashes  
Trebat će vam Windows Loader by Daz, skinite ga ovdje https://drive.google.com/file/d/1OigAwy3b9Zig1LgQ2zrBimr3J_xXLQjl/view?usp=sharing password za Windows ISO  i za Windows Loader je "kopijahorvat". Neki antivirus programi će se požaliti da su pronašli nešto zločesto. Preostaje vam vjera, ufanje, ljubav u mene koji vam garantira da je to false positive. Ako nemate vjere provjerite sa VirusTotalom i sve će vam biti jasno.
Spržite ISO na stick sa Rufus-om https://rufus.akeo.ie (svakako izaberite "MBR" pod "Partition scheme" izbornikom).
Ako imate noviju matičnu sa UEFI BIOS-om, u boot izborniku izaberite bootanje sa sticka koji je izlistan bez "UEFI" opcije ili jednostavno  isključite "UEFI" i uključite "Legacy/CMS" boot opciju u BIOS-u (jerbo UEFI boot ne podržava "legacy" MBR particije). Također uključite "AHCI" SATA mode. Secure Boot bi također trebao biti isključen.

*Ako imate računalo novije generacije (bez USB2 portova i/ili sa m.2 NVME SSD-om) moguće je da će vam instalacija zapeti jer W7 ISO nema integrirane USB3/NVME drivere. U tom slučaju upotrebite ovaj programćić: https://forum-en.msi.com/index.php?topic=261560.0
 Pažnja: navedeni program NE RADI s verzijama koje prilikom instalacije nude izbor Home/Pro, 64/32-bit ili slično. ISO mora biti "single edition" verzija.

Napravite clean install W7, aktivirajte ga sa Windows Loaderom, restartajte i provjerite uz pomoć Loadera da li je aktiviran.
(Ukoliko imate problema s aktivacijom uz pomoć Loadera, pročitajte dokumentaciju koja dolazi s njime)
Skinite Microsoftov W10  Media Creation Tool, spržite ga na stick, startajte "setup.exe" i izaberite "upgrade" opciju.
Windowsi će se automatski napraviti update na verziju identičnu postojećoj verziji W7 (Home/Pro, 64/32-bit).
Nakon što se W10 instalira, spojite se na internet, stisnite Win tipku na tipkovnici, utipkajte "activation" i uz pomoć "Activation" aplikacije provjerite da li ste dobili digitalnu licencu.
Ukoliko želite koristiti UEFI/Secure boot, uključite ga u BIOSU.
Pri svakoj sljedećoj instalaciji Windosa 10 na to računalo, morate izabrati identičnu verziju (Home/Pro, 64/32-bit) da bi digitalna aktivacija proradila.
Možete mijenjati sav hardver osim matične ploče jer je digitalna licenca vezana uz nju. Kad promjenite matičnu morate cijelu proceduru od broja 1. ponoviti.
