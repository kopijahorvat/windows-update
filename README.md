
           Doljenavedena procedura omogućit će vam da besplatno aktivirate Windows 10 putem digitalne licence

Najjednostavnije je da W10 aktivirate uz pomoć HWIDGEN aktivatora kojeg skinete ovdje: https://www.reddit.com/r/piracy/wiki/tools
HWIDGEN većina antivirusa prepoznaje kao virus/trojan jer modificira registry, no ako ga skinete sa "službenih" stranica https://www.nsaneforums.com/topic/312871-windows-10-digital-license-hwid-kms38%E2%84%A2-generation/ nema razloga za brigu. 

Malo kompliciranija ali potpuno legalna metoda je slijedeća:
Trebat će vam Windows 7 PRO SP1 ISO, kojeg nije moguće skinuti direktno od Microsofta bez aktivacijskog key-a. 
Skinite ga sa mojeg Google Drive-a https://drive.google.com/file/d/18-6Nsccs_HA8W2C25_JMnMXMl3XmQKS3
Ako ste paranoidni glede validnosti W7 ISO datoteke, usporedite SHA1 vrijednosti uz pomoć ove liste: http://naterice.com/windows-7-and-7-1-iso-names-and-sha1-hashes  
Također vam je potreban i Windows Loader programćić, skinite ga ovdje https://drive.google.com/file/d/1OigAwy3b9Zig1LgQ2zrBimr3J_xXLQjl/view?usp=sharing password za Windows ISO  i za Windows Loader je "kopijahorvat". Neki antivirus programi će se očekivano požaliti da su pronašli nešto zločesto u Windows Loader folderu. Preostaje vam vjera, ufanje, ljubav u mene koji vam garantira da je to false positive. Ako vam nedostaje istih, provjerite sa VirusTotalom i sve će vam biti jasno.
Spržite W7 ISO na stick uz pomoć Rufus-a https://rufus.akeo.ie 
Svakako izaberite "MBR" pod "Partition scheme" izbornikom te ako imate noviju matičnu sa UEFI BIOS-om, u boot izborniku izaberite bootanje sa sticka koji je izlistan bez "UEFI" opcije ili jednostavno  isključite "UEFI" i uključite "Legacy/CMS" boot opciju u BIOS-u (jerbo UEFI boot ne podržava "legacy" MBR particije). Također uključite "AHCI" SATA mode. Secure Boot bi također trebao biti isključen.

Ako imate računalo novije generacije (bez USB2 portova i/ili sa m.2 NVME SSD-om) moguće je da će vam instalacija zapeti jer W7 ISO nema integrirane USB3/NVME drivere. U tom slučaju upotrebite ovaj programćić koji će integrirati drivere: http://www.biostar.com.tw/utility/WindowsTool.zip umjesto Rufusa.
 

Napravite clean install W7, aktivirajte ga sa Windows Loaderom, restartajte i provjerite uz pomoć Loadera da li je aktiviran.
(Ukoliko imate problema s aktivacijom uz pomoć Loadera, pročitajte dokumentaciju koja dolazi s njime)
Skinite Microsoftov W10  Media Creation Tool i odaberite opciju skidanja .ISO fajla, spržite ga na stick uz pomoć Rufusa, startajte "setup.exe" i izaberite "upgrade" opciju. Alternativno možete uz pomoć 7-zip-a napraviti ekstrakciju W10 ISO-a direktno na HDD/SSD i odonuda startat setup.exe.
Nakon što se W10 instalira,  stisnite Win tipku na tipkovnici, utipkajte "activation" i uz pomoć "Activation" aplikacije provjerite da li ste dobili digitalnu licencu.
Ukoliko želite koristiti UEFI/Secure boot, uključite ga u BIOSU.

Možete mijenjati sav hardver osim matične ploče jer je digitalna licenca vezana uz HWID matične. Kad promjenite matičnu morate cijelu proceduru od broja 1. ponoviti.
