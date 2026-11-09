![Build 1](./images/Build%201.jpg)

# Build 01 – Régebbi AMD rendszer és tápegységhiba

### Áttekintés

Egy régebbi, AM3 platformra épülő asztali számítógép. Az eredeti konfiguráció viszonylag szerény volt, belépőszintű videokártyával és 500 W-os tápegységgel.

### Eredeti hardverkonfiguráció

| Alkatrész | Specifikáció |
|---|---|
| CPU | AMD Athlon II X4 640 |
| Alaplap | AM3 alaplap |
| RAM | 8GB DDR3 |
| GPU | NVIDIA GeForce GT 730 |
| Tápegység | 500W |

### Hardverhiba – Tápegység meghibásodása

Az első bekapcsolási kísérlet során a tápegység meghibásodott.

A tápegység cseréje után ellenőriztem a rendszer többi alkatrészét, hogy megállapítsam, okozott-e a meghibásodás további károkat.

Szerencsére az ellenőrzött alkatrészek túlélték az esetet, és a rendszer a tápegység cseréjét követően megfelelően működött.

### Grafikus teljesítmény

Az NVIDIA GT 730 jelentős teljesítménybeli korlátozást jelentett ebben a konfigurációban. Tapasztalataim alapján még néhány régebbi alternatíva, például a GTX 550 Ti, GTX 650 Ti vagy GT 1030 is megfelelőbb választás lett volna, az adott modelltől és felhasználási területtől függően.

### Főbb tapasztalatok

- Meghibásodott tápegység diagnosztizálása.
- Tápegység cseréje és a csatlakoztatott alkatrészek ellenőrzése.
- A rendszer működésének ellenőrzése hardverhiba után.
- Grafikus teljesítménykorlátok felismerése régebbi konfigurációknál.

---

![Build 2](./images/Build%202.jpg)

![Build 7](./images/Build%207.jpg)

# Build 02 – Saját számítógép és hardverfejlesztések

### Áttekintés

A saját asztali számítógépem, amely eredetileg az Intel 8. generációs Core platformjára épült. Az évek során több videokártya-fejlesztésen esett át, miközben az eredeti processzorplatform és a DDR4 memória megmaradt.

### Eredeti hardverkonfiguráció

| Alkatrész | Specifikáció |
|---|---|
| CPU | Intel Core i7-8700K |
| Alaplap | MSI Z370 chipsetes alaplap |
| GPU | MSI GeForce GTX 1050 |
| RAM | DDR4 |
| Platform | Intel LGA 1151 |

### Videokártya-fejlesztések

A rendszer három különböző videokártya-konfiguráción ment keresztül:

1. **MSI GTX 1050** – Az eredeti belépőszintű videokártya, amely idővel teljesítménybeli korláttá vált.
2. **ASUS ROG STRIX RX 580** – Jelentős grafikus teljesítménynövekedést biztosított, és több éven keresztül használtam.
3. **NVIDIA RTX 3070** – Jelentős fejlesztés, amely számottevően növelte a grafikus teljesítményt.

Az RTX 3070 jelenleg is a rendszerben működik. CPU-igényes feladatoknál azonban a régebbi i7-8700K platform már korlátozhatja a videokártya teljesítményének kihasználását.

### Vegyes DDR4 memóriakonfiguráció

A konfiguráció egyik érdekes sajátossága, hogy nem egyetlen, párosított memóriakészletet használ, hanem három különböző DDR4 memóriatípust:

| Memóriamodul | Sebesség | Feszültség |
|---|---|---|
| Ballistix | 2 × 4GB, 2400MHz | 1.2V |
| HyperX | 3200MHz | 1.2V |
| Kingston Fury RGB | 3600MHz | 1.35V |

Tapasztalataim szerint ezek a modulok együtt is stabilan működnek, rendszerösszeomlás nélkül.

Ez érdekes példája a DDR4 memória rugalmasságának, azonban a különböző modulok együttműködése és a névleges sebességek elérése nem garantált. A végleges működési frekvenciát és kompatibilitást az alaplap, a BIOS-beállítások és a memóriavezérlő határozzák meg.

### Főbb tapasztalatok

- Fokozatos videokártya-fejlesztések több hardvergeneráción keresztül.
- CPU- és GPU-teljesítménykorlátok felismerése.
- Különböző DDR4 memóriamodulok együttes használata.
- Memóriakompatibilitás és rendszerstabilitás vizsgálata.
- Meglévő számítógép fejlesztése a teljes platform cseréje helyett.

---

![Build 3](./images/Build%203%20Case%20Only.jpg)

*Az elkészült számítógépről sajnos nem találtam fényképet, ezért referenciaként csak a ház képét tudtam mellékelni.*

# Build 03 – Ryzen 5 8500F és RTX 3070 egyedi számítógép

### Áttekintés

Egy barátom számára megtervezett és összeszerelt egyedi asztali számítógép, aki konzolos játékról szeretett volna PC-re váltani.

Segítettem az alkatrészek kiválasztásában, a konfiguráció megtervezésében, valamint a teljes rendszer összeállításában.

### Hardverkonfiguráció

| Alkatrész | Specifikáció |
|---|---|
| CPU | AMD Ryzen 5 8500F |
| GPU | NVIDIA GeForce RTX 3070 |
| Alaplap | ASRock A620 |
| RAM | Nincs megadva |
| Tárhely | 1TB SSD |
| Tápegység | 500W |

### Indítási probléma – Nincs képkimenet

Az összeszerelést követő első bekapcsoláskor a rendszer nem adott képet.

Az első ellenőrzéseket követően áthelyeztem a RAM-modulokat az A1/B1 foglalatokból az A2/B2 foglalatokba, az alaplap ajánlott memóriabehelyezési sorrendjét követve.

A számítógép a következő indítási kísérletnél sikeresen elindult, és azóta is megfelelően működik.

### Videokártya ellenőrzése

Az összeszerelés során a használt RTX 3070 hűtőbordáján látható korróziót is észrevettem.

A videokártya korábbi használati és tárolási körülményei ismeretlenek voltak. A jelenség lehetséges okai között szerepelhet nedvességnek való kitettség vagy tartósan párás környezetben történő tárolás, azonban a pontos okot pusztán szemrevételezéssel nem lehetett megállapítani.

A kártya a tesztelés során működőképes volt.

### Főbb tapasztalatok

- Teljes PC-konfiguráció megtervezése egy első PC-t vásárló felhasználó számára.
- Alkatrészválasztás és hardveres összeszerelés.
- Képkimenet nélküli indítási probléma diagnosztizálása.
- Az alaplapi RAM-foglalatok megfelelő használatának megismerése.
- Használt hardverek ellenőrzése beszerelés előtt.
- A rendszer működésének ellenőrzése az összeszerelést követően.

---

![Build 4](./images/Build%204.jpg)

# Build 04 – AMD Phenom II X6 1090T rendszer

### Hardverkonfiguráció

| Alkatrész | Specifikáció |
|---|---|
| CPU | AMD Phenom II X6 1090T |
| Alaplap | ASUS AM3 |
| RAM | 8GB (2 × 4GB) DDR3 1600MHz, Dual Channel |
| GPU | Sapphire AMD Radeon R9 280X |
| Tápegység | 600W |
| Tárhely | 500GB HDD, 5200 RPM |

### Hibadiagnosztika és hibaelhárítás

Ez volt az egyik legkiszámíthatatlanabb számítógép, amellyel valaha dolgoztam. Visszatérő, időszakos képkimeneti problémával küzdött, különösen áramszünet vagy a tápkábel kihúzása után.

A hiba jelentkezésekor a számítógép bekapcsolt, de nem adott képet, és a megszokott POST-hangjelzés sem hallatszott. Érdekes módon egy idő után, ha a számítógép ismét áram alatt maradt, gyakran újra működőképessé vált.

Kezdetben a videokártyára vagy a memóriára gyanakodtam, mivel mindkettő okozhat indítási és képkimeneti problémákat.

**Hibaelhárítási folyamat:**

1. **Videokártya cseréje:** A Sapphire R9 280X cseréje után a probléma továbbra is fennállt.
2. **RAM cseréje:** Körülbelül egy évvel később a memóriamodulokat is lecseréltem, de az alaplap továbbra is produkálta ugyanazt a hibát.
3. **Platformcsere:** Végül az alaplapot, a processzort és a memóriát egy Intel platformra cseréltem.

Mivel a probléma a videokártya és a memória cseréje után is megmaradt, az alaplap vált a hiba legvalószínűbb forrásává.

### Végleges hardverfejlesztés

| Alkatrész | Cserealkatrész |
|---|---|
| CPU | Intel Core i5-3570 |
| Alaplap | H61 chipsetes alaplap |
| RAM | 16GB (2 × 8GB) DDR3 1600MHz, Dual Channel |

A platform teljes cseréje után a visszatérő képkimeneti probléma teljesen megszűnt.

### További megfigyelés – Hőtermelés

Az eredeti Phenom II X6 1090T rendszer működés közben rendkívül magas hőmérsékletet produkált.

Annak ellenére, hogy viszonylag nagyméretű processzorhűtő volt rajta, körülbelül 30 perc működés után a számítógép rendkívül forróvá vált. Egyes esetekben a számítógépház külső felülete is kellemetlenül forró volt érintésre.

A túlzott hőtermelés pontos oka nem derült ki, de ez is a rendszer egyik különösen szokatlan tulajdonsága volt.

### Főbb tapasztalatok

- Időszakos POST- és képkimeneti hibák diagnosztizálása.
- Több hardverkomponens egyenkénti ellenőrzése.
- Az alaplap mint valószínű hibaforrás azonosítása.
- Hardverplatform teljes cseréje a rendszer stabilitásának helyreállításához.
- Hosszú távú rendszerstabilitás és hőtermelés megfigyelése.

![Build 5](./images/Build%205.jpg)

# Build 05 – Ubuntu Linux platformmigráció

### Eredeti hardverkonfiguráció

| Alkatrész | Specifikáció |
|---|---|
| CPU | Intel Core i5-4690K |
| Alaplap | MSI Z87 chipset, LGA 1150 |
| RAM | 16GB DDR3 1600MHz (2 × 4GB + 1 × 8GB) |
| GPU | NVIDIA GeForce GTX 1050 Ti |
| Operációs rendszer | Ubuntu Linux |

### Platformfejlesztés

Az eredeti tulajdonos egy barátjától kapott egy másik számítógépet, amelyre már nem volt szüksége. Az újonnan kapott rendszer Ryzen 5 processzort és 16GB DDR4 memóriát tartalmazott, így lehetőség nyílt a meglévő számítógép hardveres fejlesztésére.

A rendelkezésre álló alkatrészek közül a jobb minőségű, 80 PLUS tanúsítvánnyal rendelkező tápegységet választottam ki, majd a Ryzen-alapú platformot az eredeti Intel konfiguráció helyére építettem be. A GTX 1050 Ti videokártyát megtartottam.

### Hardverkonfiguráció a fejlesztés után

| Alkatrész | Specifikáció |
|---|---|
| CPU | AMD Ryzen 5 (pontos modell nem ismert) |
| Alaplap | AMD-kompatibilis alaplap (pontos modell nem ismert) |
| RAM | 16GB DDR4 2600MHz (2 × 8GB) |
| GPU | NVIDIA GeForce GTX 1050 Ti |
| Tápegység | Jobb minőségű, 80 PLUS tanúsítvánnyal rendelkező tápegység |
| Operációs rendszer | Meglévő Ubuntu Linux telepítés |

### Linux-kompatibilitás és hibaelhárítás

A fejlesztés egyik legérdekesebb része a már meglévő Ubuntu Linux rendszer volt. Kíváncsi voltam, hogyan kezeli a Linux a teljes hardverplatform cseréjét, különösen az Intel processzorról és alaplapról AMD-alapú rendszerre történő átállást.

Meglepetésemre az Ubuntu már az első indítási kísérlet során sikeresen elindult, és nem volt szükség az operációs rendszer újratelepítésére.

A kezdeti teljesítmény kissé lassú volt, azonban a szükséges illesztőprogramok és platformbeállítások rendezése után a rendszer érezhetően reszponzívabbá vált.

A sikeres migráció jól szemléltette, hogy a Linux képes jelentős hardverváltoztatásokat kezelni egy meglévő operációs rendszer telepítésének megtartása mellett.

### Főbb tapasztalatok

- Meglévő Ubuntu telepítés tesztelése teljes Intel–AMD platformváltás után.
- Az operációs rendszer sikeres elindítása újratelepítés nélkül.
- A fejlesztés utáni illesztőprogram- és konfigurációs problémák kezelése.
- Meglévő hardverek újrahasznosítása a rendszer fejlesztése mellett.
- Gyakorlati tapasztalat szerzése a Linux hardverkompatibilitásával és rendszer-migrációjával kapcsolatban.

### Személyes tapasztalatok

Ez a projekt tovább növelte az érdeklődésemet a Linux és a nyílt forráskódú operációs rendszerek iránt. Az Ubuntu és más Linux-disztribúciók egyre felhasználóbarátabbá váltak, miközben a hardvertámogatás, a használhatóság és az elérhető szoftverek köre is folyamatosan fejlődik.

Különösen érdekesnek tartom a zárt, saját tulajdonú szoftverektől való függetlenedés lehetőségét, valamint az egyre szélesebb körben elérhető, könnyűsúlyú Linux-disztribúciókat. A Linux napjainkban egyre életképesebb alternatívát jelent az általános számítógépes felhasználásban is, nem csupán speciális technikai környezetekben.

---

![Build 6](./images/Build%206.jpg)

# Build 06 – ASUS TUF RTX 3080 gamer PC

### Hardverkonfiguráció

| Alkatrész | Specifikáció |
|---|---|
| CPU | AMD Ryzen 7 5700G |
| GPU | ASUS TUF Gaming GeForce RTX 3080 OC 10GB |
| RAM | 32GB DDR4 |
| Tárhely | 1TB SSD + HDD |
| Tápegység | 650W |
| Operációs rendszer | Windows 11 |

### Kiindulási állapot

Ez egy használt számítógép volt, amelyet a vásárlás előtt már teszteltek. A vásárló korábban kizárólag konzolokat használt, ezért viszonylag kevés tapasztalattal rendelkezett az asztali számítógépek hardverével kapcsolatban.

A rendszer kezdetben jó állapotúnak tűnt. Mindkét háttértár viszonylag kevés használatot mutatott, a Windows 11 pedig frissen volt telepítve az SSD-re.

Körülbelül két nap normál használat után azonban indítási probléma jelentkezett.

### Hibadiagnosztika

Bekapcsoláskor a számítógép minden alkalommal az ASUS alaplapi indítóképernyőjénél akadt el. A többszöri újraindítás sem oldotta meg a problémát.

Néhány újraindítás után szokatlan, kattogó és kopogó hang kezdett hallatszani a számítógépház belsejéből.

Eltávolítottam az oldallapot, majd ellenőriztem a ventilátorokat, a tápegységet és a többi mozgó alkatrészt, hogy megtaláljam a zaj forrását. Végül kiderült, hogy a hang a másodlagos HDD felől érkezik.

### Hibaelhárítás és megoldás

Mivel a Windows 11 az SSD-re volt telepítve, a HDD-n pedig nem voltak fontos adatok, leválasztottam a másodlagos meghajtót a hiba forrásának elkülönítése érdekében.

A HDD leválasztása után:

- A rendszer sikeresen túljutott az ASUS alaplapi indítóképernyőjén.
- A Windows 11 normálisan elindult az SSD-ről.
- A számítógép további indítási problémák nélkül működött.

A hibás HDD-t így sikerült azonosítani az indítási probléma forrásaként.

### Végső eredmény

A számítógép az SSD használatával továbbra is megfelelően működött. A tulajdonos azóta is problémamentesen használja a rendszert, és elégedett a számítógéppel.

### Főbb tapasztalatok

- Egy másodlagos háttértár is megakadályozhatja a számítógép sikeres elindulását, még akkor is, ha az operációs rendszer egy másik meghajtóra van telepítve.
- A mechanikus HDD-kből érkező szokatlan zajok fizikai meghibásodásra utalhatnak.
- Az egyes hardverkomponensek leválasztása hatékony módszer a hibaforrás elkülönítésére.
- A rendszerindítási folyamat ismerete segít megkülönböztetni a háttértárral kapcsolatos problémákat az alaplapi vagy operációs rendszerhibáktól.
