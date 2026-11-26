# SERVIBE
## Részletes projekt- és rendszerkövetelmény-specifikáció

**Projekt neve:** ServiBe  
**Projekt típusa:** Webalapú szakemberkereső és szolgáltatáskezelő platform  
**Fejlesztők:** Hujber Enzó Meliton és Horváth Dániel Gábor  
**Intézmény:** Bajai SZC Türr István Technikum – 13.A  
**Képzés:** Szoftverfejlesztő  
**Célpiac:** Magyarország  
**Frontend:** Angular, TypeScript, HTML, SCSS, Bootstrap  
**Backend:** Node.js, Express.js  
**Adatbázis:** MySQL  
**Verziókezelés:** Git, GitHub  

---

# 1. A projekt bemutatása

## 1.1. A projekt alapötlete

A ServiBe egy olyan webalapú szakemberkereső és szolgáltatáskezelő platform, amelynek célja, hogy összekapcsolja a szolgáltatást kereső ügyfeleket a különböző szolgáltatásokat kínáló szakemberekkel, vállalkozásokkal és magánszemélyekkel.

A rendszer lehetőséget biztosít arra, hogy a felhasználók egyetlen felületen kereshessenek számukra megfelelő szolgáltatót, megtekinthessék annak bemutatkozását, szolgáltatásait, árait, referenciáit és értékeléseit, valamint kapcsolatba léphessenek vele.

A platform nem csupán egy egyszerű szakember-adatbázis. A cél egy olyan komplex rendszer létrehozása, amely a szolgáltatás igénybevételének teljes folyamatát támogatja a kereséstől egészen a munka elvégzéséig és értékeléséig.

A ServiBe központi célkitűzése, hogy a szolgáltatások keresése, az ajánlatkérés, az időpontfoglalás és a kommunikáció egyetlen, átlátható rendszerben történjen.

**Szlogen:** „Találd meg. Foglald le. Intézd.”

## 1.2. A projekt célja

A fejlesztés elsődleges célja egy korszerű, biztonságos, felhasználóbarát és reszponzív webalkalmazás létrehozása.

A platform céljai:

- A szolgáltatást kereső ügyfelek és a szolgáltatók összekapcsolása.
- A szakemberek és szolgáltatások egyszerű kereshetőségének biztosítása.
- A szolgáltatók online jelenlétének és láthatóságának növelése.
- Az ajánlatkérés és ajánlatadás folyamatának egyszerűsítése.
- Az időpontfoglalás és a szolgáltatások kezelésének támogatása.
- A szolgáltatók és ügyfelek közötti kommunikáció biztosítása.
- Az elvégzett szolgáltatások értékelhetősége.
- A megbízhatóság növelése ellenőrzési és értékelési rendszerrel.

Hosszú távon a ServiBe célja egy olyan magyarországi szolgáltatói piactér kialakítása, amely különböző szolgáltatási területeket fog össze.

## 1.3. A probléma, amelyre megoldást nyújt

A szolgáltatások keresése sok esetben több különböző weboldal, közösségi médiafelület, hirdetési oldal és személyes ajánlás átnézését igényli.

Az ügyfelek gyakran nehezen tudják összehasonlítani a szolgáltatók árait, tapasztalatait, elérhetőségét és megbízhatóságát.

A szolgáltatók számára szintén problémát jelenthet az ügyfelek elérése, az ajánlatkérések kezelése, az időpontok nyilvántartása és a kommunikáció rendszerezése.

A ServiBe ezeket a problémákat egy közös platformon kívánja kezelni.

## 1.4. A platform értékajánlata

A ServiBe legfontosabb előnye, hogy a szolgáltatással kapcsolatos folyamatokat egy rendszerben egyesíti.

Az ügyfél számára:

- Egyszerű keresés.
- Összehasonlítható szolgáltatói profilok.
- Átlátható értékelések.
- Közvetlen kapcsolatfelvétel.
- Ajánlatkérés és ajánlatok összehasonlítása.
- Online időpontfoglalás.
- Korábbi ügyek és foglalások nyomon követése.

A szolgáltató számára:

- Saját online profil.
- Szolgáltatások és árak kezelése.
- Ügyfelek elérése.
- Ajánlatkérések fogadása.
- Egyedi ajánlatok készítése.
- Naptár és foglalások kezelése.
- Ügyfélkommunikáció.
- Értékelések és referenciák bemutatása.

---

# 2. Célközönség és célpiac

## 2.1. Földrajzi célterület

A platform kezdetben kizárólag Magyarország területén működik.

A keresés során a felhasználók megadhatják a települést, a vármegyét, illetve igény szerint a keresési körzetet.

A későbbi fejlesztési célok között szerepelhet a külföldi piacokra történő terjeszkedés.

## 2.2. Ügyfelek

A rendszer elsődleges felhasználói azok a magánszemélyek, akik valamilyen szolgáltatást szeretnének igénybe venni.

Például:

- Villanyszerelőt keresnek egy lakásfelújításhoz.
- Takarítót keresnek otthonuk rendszeres takarításához.
- Fodrászhoz szeretnének időpontot foglalni.
- Magántanárt keresnek.
- Autószerelőt keresnek.
- Fotóst keresnek egy rendezvényhez.
- Informatikai segítségre van szükségük.

## 2.3. Szolgáltatók

A rendszerben többféle szolgáltató regisztrálhat:

- Egyéni vállalkozók.
- Cégek és vállalkozások.
- Önálló szakemberek.
- Megfelelő képesítéssel rendelkező magánszemélyek.
- Nem engedélyköteles tevékenységet végző magánszemélyek.

A szabályozott tevékenységeknél a rendszernek lehetőséget kell biztosítania a szükséges képesítések és engedélyek ellenőrzésére.

Fontos, hogy a platform különbséget tegyen a személyazonosság ellenőrzése és a szakmai képesítés ellenőrzése között.

---

# 3. Szolgáltatási kategóriák

A ServiBe több szolgáltatási területet fog össze.

## 3.1. Építőipar és felújítás

- Villanyszerelés.
- Vízszerelés.
- Festés és mázolás.
- Burkolás.
- Asztalosmunkák.
- Kőművesmunkák.
- Gipszkartonozás.
- Tetőfedés.
- Lakásfelújítás.

## 3.2. Otthon és háztartás

- Lakástakarítás.
- Irod takarítás.
- Kertgondozás.
- Fűnyírás.
- Költöztetés.
- Bútorösszeszerelés.
- Háztartási segítség.
- Ingatlan-karbantartás.

## 3.3. Járművek és autóipar

- Autószerelés.
- Gumiszerviz.
- Autókozmetika.
- Autóvillamosság.
- Járműdiagnosztika.

## 3.4. Szépségápolás és wellness

- Fodrászat.
- Kozmetika.
- Manikűr és pedikűr.
- Masszázs.
- Smink.
- Egyéb szépségápolási szolgáltatások.

## 3.5. Kreatív szolgáltatások

- Fotózás.
- Videózás.
- Grafikai tervezés.
- Webdesign.
- Dekoráció.
- Rendezvényszervezés.

## 3.6. Oktatás és képzés

- Magántanítás.
- Nyelvoktatás.
- Zeneoktatás.
- Informatikai oktatás.
- Felvételi és vizsgafelkészítés.

## 3.7. Informatika és technológia

- Számítógép-javítás.
- Laptopjavítás.
- Informatikai segítségnyújtás.
- Weboldalkészítés.
- Programozás.
- Hálózati szolgáltatások.

## 3.8. Állatokkal kapcsolatos szolgáltatások

- Kutyasétáltatás.
- Kisállat-felügyelet.
- Kisállat-gondozás.
- Állatkozmetika.

A kategóriák és alkategóriák kezelése adminisztrátori jogosultsághoz kötött. Az adminisztrátor új kategóriákat hozhat létre, módosíthatja vagy inaktiválhatja a meglévőket.

---

# 4. Felhasználói szerepkörök és jogosultságok

A rendszer négy alapvető felhasználói szerepkört különböztet meg.

## 4.1. Vendég

A vendég még nem rendelkezik regisztrált felhasználói fiókkal.

Jogosultságai:

- Főoldal megtekintése.
- Szolgáltatási kategóriák böngészése.
- Szolgáltatók keresése.
- Keresési szűrők használata.
- Nyilvános szolgáltatói profilok megtekintése.
- Nyilvános értékelések megtekintése.
- Regisztráció és bejelentkezés.

A vendég nem küldhet ajánlatkérést, nem foglalhat időpontot, nem küldhet üzenetet és nem írhat értékelést.

## 4.2. Ügyfél

Az ügyfél regisztrált felhasználó, aki szolgáltatásokat szeretne igénybe venni.

Jogosultságai:

- Saját profil kezelése.
- Szolgáltatók keresése.
- Szolgáltatói profilok megtekintése.
- Szolgáltatók kedvencekhez adása.
- Ajánlatkérés létrehozása.
- Ajánlatok megtekintése.
- Ajánlat elfogadása vagy elutasítása.
- Időpontfoglalás.
- Foglalások módosítása vagy lemondása a szabályok szerint.
- Üzenetküldés.
- Értesítések megtekintése.
- Korábbi szolgáltatások megtekintése.
- Elvégzett szolgáltatások értékelése.
- Saját adatok és beállítások módosítása.

Egy ügyfél később szolgáltatói profilt is létrehozhat, így ugyanazzal a fiókkal mindkét szerepben használhatja a rendszert.

## 4.3. Szolgáltató

A szolgáltató olyan regisztrált felhasználó, aki saját szolgáltatásokat kínál a platformon.

Jogosultságai:

- Szolgáltatói profil létrehozása.
- Bemutatkozás és elérhetőségek kezelése.
- Szolgáltatási kategóriák kiválasztása.
- Saját szolgáltatások létrehozása.
- Szolgáltatások módosítása és inaktiválása.
- Árak és díjszabások beállítása.
- Referenciaképek feltöltése.
- Munkaterület és kiszállási terület megadása.
- Képesítések és engedélyek benyújtása ellenőrzésre.
- Ajánlatkérések fogadása.
- Egyedi ajánlatok készítése.
- Időpontok és foglalások kezelése.
- Ügyfelekkel történő kommunikáció.
- Értékelések megtekintése.
- Értékelésekre adott válaszok.
- Statisztikák megtekintése.
- Előfizetési csomag kezelése.

A szolgáltató csak a saját profilját, szolgáltatásait, ajánlatait, foglalásait és beszélgetéseit kezelheti.

## 4.4. Adminisztrátor

Az adminisztrátor a platform működésének felügyeletéért felelős.

Jogosultságai:

- Felhasználók kezelése.
- Szolgáltatók kezelése.
- Szolgáltatói ellenőrzések elbírálása.
- Kategóriák és alkategóriák kezelése.
- Szolgáltatások moderálása.
- Bejelentések és panaszok kezelése.
- Értékelések moderálása.
- Felhasználói fiókok korlátozása vagy felfüggesztése.
- Előfizetési csomagok kezelése.
- Rendszerstatisztikák megtekintése.
- Rendszerbeállítások kezelése.
- Adminisztrátori tevékenységek naplózása.

Az adminisztrátori funkciókat kizárólag megfelelő jogosultsággal rendelkező felhasználó érheti el.

---

# 5. Részletes funkcionális követelmények

## 5.1. Főoldal

A főoldal a rendszer elsődleges belépési pontja.

Feladata, hogy bemutassa a platform célját, és segítsen a látogatóknak gyorsan megtalálni a keresett szolgáltatást.

A főoldal elemei:

- ServiBe logó és navigációs menü.
- Keresősáv szolgáltatás és település megadásához.
- Népszerű szolgáltatási kategóriák.
- Kiemelt szolgáltatók.
- Frissen regisztrált szolgáltatók.
- A platform működésének rövid bemutatása.
- Regisztrációs és bejelentkezési lehetőség.
- Szolgáltatói regisztrációra ösztönző rész.
- Gyakran ismételt kérdések.
- Kapcsolatfelvételi lehetőség.
- Adatvédelmi tájékoztató és felhasználási feltételek.

A főoldalnak reszponzívnak kell lennie, és mobiltelefonon is könnyen használhatónak kell maradnia.

## 5.2. Regisztráció

A rendszer lehetőséget biztosít új felhasználói fiók létrehozására.

A regisztráció során bekérendő adatok:

- Teljes név.
- Felhasználónév.
- E-mail-cím.
- Jelszó.
- Jelszó megerősítése.
- Adatkezelési tájékoztató és felhasználási feltételek elfogadása.

Követelmények:

- Az e-mail-cím egyedisége.
- A jelszó megfelelő erősségének ellenőrzése.
- A két jelszómező egyezőségének vizsgálata.
- Kötelező mezők ellenőrzése.
- Hibás adatok esetén érthető visszajelzés.
- A jelszó biztonságos, visszafejthetetlen formában történő tárolása.
- Sikeres regisztráció után a felhasználó bejelentkezhet.

A szolgáltatói profil létrehozása nem kötelező a regisztráció pillanatában. Az ügyfél később is aktiválhatja a szolgáltatói funkciókat.

## 5.3. Bejelentkezés és kijelentkezés

A felhasználó e-mail-cím és jelszó segítségével jelentkezhet be.

A rendszer feladatai:

- A megadott adatok ellenőrzése.
- A felhasználó azonosítása.
- Jogosultságok betöltése.
- Hitelesítési állapot kezelése.
- Sikeres bejelentkezés után a megfelelő felület megjelenítése.
- Kijelentkezéskor a munkamenet biztonságos lezárása.

Hibás bejelentkezési adatok esetén a rendszer általános, biztonságos hibaüzenetet jelenít meg.

A későbbi fejlesztések között szerepelhet az e-mailes jelszó-visszaállítás és a kétlépcsős azonosítás.

## 5.4. Felhasználói profil

Minden regisztrált felhasználó rendelkezik saját profiloldallal.

A profilban szereplő adatok:

- Teljes név.
- Felhasználónév.
- E-mail-cím.
- Profilkép.
- Regisztráció időpontja.
- Fiók állapota.
- Fiókbeállítások.

A felhasználó módosíthatja saját adatait, profilképét és jelszavát.

Az e-mail-cím módosításakor új e-mailes megerősítés alkalmazható.

## 5.5. Szolgáltatói profil

A szolgáltatói profil a szolgáltató nyilvános bemutatkozó oldala.

Tartalma:

- Szolgáltató neve vagy vállalkozás neve.
- Profilkép vagy céges logó.
- Rövid bemutatkozás.
- Részletes leírás.
- Szolgáltatási kategóriák.
- Elérhető szolgáltatások.
- Árak vagy díjszabási információk.
- Működési terület.
- Kiszállási lehetőségek.
- Referenciaképek.
- Értékelések.
- Ellenőrzési státusz.
- Foglalási lehetőség.
- Ajánlatkérési lehetőség.
- Üzenetküldési lehetőség.

A szolgáltató saját profilját bármikor módosíthatja.

A profil csak akkor jelenhet meg nyilvánosan, ha megfelel a platform közzétételi feltételeinek.

## 5.6. Szolgáltatások kezelése

A szolgáltató több különböző szolgáltatást is létrehozhat.

Egy szolgáltatás adatai:

- Szolgáltatás neve.
- Kategória.
- Alkategória.
- Leírás.
- Ár.
- Árazási mód.
- Várható időtartam.
- Szolgáltatás helye.
- Kiszállási lehetőség.
- Kapcsolódó képek.
- Aktív vagy inaktív állapot.

Lehetséges árazási módok:

- Fix ár.
- Óradíj.
- Négyzetméter alapú díj.
- Egyedi ajánlat alapján meghatározott ár.

A szolgáltató saját szolgáltatásait létrehozhatja, módosíthatja, inaktiválhatja és törölheti a rendszer szabályai szerint.

## 5.7. Szolgáltatók keresése

A keresési funkció a platform egyik legfontosabb eleme.

A felhasználó az alábbiak alapján kereshet:

- Szolgáltatás neve.
- Kategória.
- Alkategória.
- Település.
- Vármegye.
- Keresési távolság.
- Értékelés.
- Ár.
- Ellenőrzött státusz.
- Elérhető időpont.
- Szolgáltatás helye.

A szolgáltatás helye lehet:

- A szolgáltató telephelyén.
- Az ügyfél által megadott helyszínen.
- Online.

Rendezési lehetőségek:

- Legrelevánsabb találatok.
- Legjobb értékelés.
- Legolcsóbb szolgáltatás.
- Legmagasabb ár.
- Legújabb szolgáltatók.

A találatok kártyás elrendezésben jelennek meg.

Egy találati kártya tartalmazza:

- Profilképet.
- Szolgáltató nevét.
- Fő szolgáltatási kategóriát.
- Rövid leírást.
- Értékelést.
- Helyszínt.
- Ártól vagy díjszabástól kezdődő információt, ha rendelkezésre áll.
- Ellenőrzési jelölést.
- Profil megtekintése lehetőséget.

A keresési eredményeket lapozással vagy fokozatos betöltéssel kell megjeleníteni.

## 5.8. Kedvencek

Az ügyfelek kedvenc szolgáltatókat menthetnek el.

Funkciók:

- Szolgáltató hozzáadása a kedvencekhez.
- Szolgáltató eltávolítása a kedvencek közül.
- Kedvencek listájának megtekintése.
- Kedvenc szolgáltatói profil megnyitása.

Egy felhasználó ugyanazt a szolgáltatót csak egyszer mentheti el a kedvencei közé.

## 5.9. Ajánlatkérés

Az ajánlatkérés lehetővé teszi, hogy az ügyfél részletesen leírja az elvégzendő munkát.

Az ajánlatkérés adatai:

- Megnevezés.
- Szolgáltatási kategória.
- Részletes leírás.
- Helyszín.
- Kívánt időpont vagy időszak.
- Tervezett költségkeret, opcionálisan.
- Csatolt képek.
- Kiválasztott szolgáltató vagy szolgáltatók.

Az ajánlatkérés egy vagy több megfelelő szolgáltatóhoz is eljuttatható.

A szolgáltató értesítést kap az új ajánlatkérésről.

Az ügyfél a saját ajánlatkéréseit egy külön felületen kezelheti.

Állapotok:

- Függőben.
- Ajánlatra vár.
- Ajánlat érkezett.
- Lezárt.
- Visszavont.

## 5.10. Ajánlatadás

A szolgáltató az ajánlatkérés alapján egyedi ajánlatot készíthet.

Az ajánlat tartalmazza:

- Ajánlott árat.
- A munka részletes leírását.
- Várható időtartamot.
- Lehetséges időpontokat.
- Érvényességi időt.
- Egyéb feltételeket.

Az ügyfél az ajánlatot:

- Elfogadhatja.
- Elutasíthatja.
- A megadott érvényességi idő lejárta előtt visszautasíthatja vagy további egyeztetést kezdeményezhet.

Az ajánlat elfogadása után a rendszer lehetőséget biztosít a kapcsolódó időpontfoglalás létrehozására.

Ajánlati státuszok:

- Függőben.
- Elküldve.
- Elfogadva.
- Elutasítva.
- Lejárt.
- Visszavont.

Az ajánlatokhoz kapcsolódó módosításokat és állapotváltozásokat a rendszer nyilvántartja.

## 5.11. Időpontfoglalás

A szolgáltató megadhatja az elérhető időpontjait.

A foglalási rendszer feladata, hogy az ügyfél számára megjelenítse a szabad időpontokat, és megakadályozza az ugyanarra az időszakra történő ütköző foglalásokat.

A foglalás adatai:

- Ügyfél.
- Szolgáltató.
- Kapcsolódó szolgáltatás.
- Foglalás dátuma.
- Kezdési idő.
- Befejezési idő vagy időtartam.
- Helyszín.
- Megjegyzés.
- Foglalás állapota.

Foglalási státuszok:

- Függőben.
- Megerősítve.
- Teljesítve.
- Elutasítva.
- Lemondva.
- Nem jelent meg.

A szolgáltató beállíthatja, hogy a foglalások automatikusan vagy manuális jóváhagyás után legyenek véglegesek.

A foglalás módosításáról és lemondásáról mindkét érintett fél értesítést kap.

A foglalási ütközéseket backendoldali ellenőrzéssel és adatbázis-tranzakciókkal kell kezelni.

## 5.12. Üzenetküldés

A platform belső üzenetküldő rendszert biztosít az ügyfelek és szolgáltatók közötti kommunikációhoz.

Funkciók:

- Beszélgetések létrehozása.
- Üzenetek küldése.
- Üzenetek fogadása.
- Beszélgetések listázása.
- Küldési idő megjelenítése.
- Olvasottsági állapot.
- Kapcsolódó ajánlat vagy foglalás megjelenítése.

A beszélgetéseket kizárólag azok a felhasználók érhetik el, akik a beszélgetés résztvevői.

Az első változatban hagyományos, adatbázis-alapú üzenetküldés is elegendő. Később Socket.IO segítségével valós idejű kommunikáció is kialakítható.

## 5.13. Értékelési rendszer

Az ügyfelek a teljesített szolgáltatásokat értékelhetik.

Az értékelés tartalma:

- 1–5 csillagos pontszám.
- Szöveges vélemény.
- Értékelés dátuma.
- Kapcsolódó szolgáltatás vagy foglalás.

Követelmények:

- Csak teljesített szolgáltatáshoz lehessen értékelést létrehozni.
- Egy teljesített foglaláshoz egy ügyfél egy értékelést írhasson.
- A szolgáltató válaszolhasson az értékelésre.
- A nem megfelelő tartalom bejelenthető legyen.
- Az adminisztrátor moderálhassa a szabályzatba ütköző értékeléseket.

A szolgáltató átlagos értékelése a profilján is megjelenik.

## 5.14. Értesítési rendszer

A rendszer értesítéseket küld a fontos eseményekről.

Értesítési események:

- Új ajánlatkérés érkezett.
- Új ajánlat érkezett.
- Ajánlatot elfogadtak vagy elutasítottak.
- Új üzenet érkezett.
- Foglalást megerősítettek.
- Foglalást módosítottak.
- Foglalást lemondtak.
- Közeledik a foglalás időpontja.
- Új értékelés érkezett.
- A szolgáltatói ellenőrzés eredménye megérkezett.

Az első változatban az értesítések a felhasználói felületen jelennek meg.

Később e-mailes és mobilos push értesítések is kialakíthatók.

## 5.15. Szolgáltatói ellenőrzés

A ServiBe fontos célja a platform megbízhatóságának növelése.

A szolgáltató ellenőrzési folyamaton mehet keresztül.

A folyamat lépései:

1. A szolgáltató megadja a szükséges adatokat.
2. Feltölti az adott tevékenységhez szükséges dokumentumokat.
3. A rendszer ellenőrzésre váró státuszba helyezi a kérelmet.
4. Az adminisztrátor megvizsgálja a benyújtott adatokat.
5. Az adminisztrátor elfogadja, elutasítja vagy hiánypótlásra visszaküldi a kérelmet.
6. A szolgáltató értesítést kap a döntésről.

Ellenőrzési állapotok:

- Nincs benyújtva.
- Ellenőrzés alatt.
- Elfogadva.
- Elutasítva.
- Hiánypótlás szükséges.
- Felfüggesztve.

A rendszernek különbséget kell tennie az alábbiak között:

- Személyazonosság vagy szolgáltatói adatok ellenőrzése.
- Szakmai képesítés vagy engedély ellenőrzése.

Nem minden szolgáltatási tevékenység igényel szakmai képesítést vagy hatósági engedélyt. A követelményeket az adott tevékenység szabályaihoz kell igazítani.

Az ellenőrzési jelölés pontosan azt mutathatja, amit a platform ténylegesen ellenőrzött. Nem jelent automatikus garanciát a szolgáltatás minőségére.

A feltöltött dokumentumokat biztonságosan, korlátozott hozzáféréssel kell tárolni.

## 5.16. Adminisztrációs felület

Az adminisztrációs felület kizárólag adminisztrátori jogosultsággal érhető el.

Főbb modulok:

**Vezérlőpult**
- Regisztrált felhasználók száma.
- Szolgáltatók száma.
- Aktív szolgáltatások száma.
- Új ajánlatkérések száma.
- Foglalások száma.
- Ellenőrzésre váró szolgáltatók.

**Felhasználókezelés**
- Felhasználók listázása.
- Keresés és szűrés.
- Felhasználói adatok megtekintése.
- Fiókok korlátozása.
- Fiókok felfüggesztése.

**Szolgáltatókezelés**
- Szolgáltatói profilok listázása.
- Ellenőrzési kérelmek megtekintése.
- Dokumentumok ellenőrzése.
- Ellenőrzési státusz módosítása.

**Kategóriakezelés**
- Új kategória létrehozása.
- Kategória módosítása.
- Alkategóriák kezelése.
- Kategóriák inaktiválása.

**Tartalommoderálás**
- Szolgáltatások ellenőrzése.
- Értékelések kezelése.
- Bejelentések feldolgozása.

**Rendszerfelügyelet**
- Statisztikák.
- Előfizetési csomagok.
- Adminisztrátori tevékenységek naplója.

---

# 6. Felhasználói munkafolyamatok

## 6.1. Szolgáltatás keresésének folyamata

1. A látogató megnyitja a ServiBe főoldalát.
2. Megadja a keresett szolgáltatást.
3. Megadja a települést.
4. A rendszer megjeleníti a találatokat.
5. A látogató szűrőket alkalmazhat.
6. Megnyitja egy szolgáltató profilját.
7. Megtekinti a szolgáltatásokat, árakat és értékeléseket.
8. Regisztráció vagy bejelentkezés után ajánlatot kérhet vagy időpontot foglalhat.

## 6.2. Ajánlatkérés folyamata

1. Az ügyfél kiválaszt egy szolgáltatót.
2. Kitölti az ajánlatkérési űrlapot.
3. Megadja a munka részleteit.
4. Szükség esetén képeket csatol.
5. Elküldi az ajánlatkérést.
6. A szolgáltató értesítést kap.
7. A szolgáltató elkészíti az ajánlatot.
8. Az ügyfél megtekinti és elfogadja vagy elutasítja azt.
9. Elfogadás esetén időpontfoglalás vagy további egyeztetés következik.

## 6.3. Szolgáltatói regisztráció folyamata

1. A felhasználó létrehozza saját fiókját.
2. Kiválasztja a szolgáltatói profil létrehozását.
3. Megadja a szolgáltatói adatokat.
4. Kiválasztja a szolgáltatási kategóriákat.
5. Feltölti a szükséges bemutatkozó képeket.
6. Megadja a működési területét.
7. Szükség esetén benyújtja az ellenőrzéshez szükséges dokumentumokat.
8. Az adminisztrátor elvégzi az ellenőrzést.
9. A megfelelő feltételek teljesülése után a profil nyilvánossá válhat.

## 6.4. Időpontfoglalás folyamata

1. Az ügyfél megnyitja a szolgáltató profilját.
2. Kiválasztja a szolgáltatást.
3. Megtekinti az elérhető időpontokat.
4. Kiválasztja a megfelelő időpontot.
5. Megadja a szükséges adatokat.
6. Elküldi a foglalási kérelmet.
7. A szolgáltató jóváhagyja vagy elutasítja a foglalást, ha manuális megerősítés szükséges.
8. A rendszer mindkét fél számára visszajelzést küld.
9. A szolgáltatás teljesítése után a foglalás lezárható és értékelhető.

---

# 7. Felhasználói felület és oldalszerkezet

## 7.1. Nyilvános oldalak

- Főoldal.
- Szolgáltatási kategóriák.
- Keresési eredmények.
- Szolgáltatói profil.
- Szolgáltatás részletei.
- Hogyan működik?
- Rólunk.
- Kapcsolat.
- Gyakran ismételt kérdések.
- Regisztráció.
- Bejelentkezés.
- Adatvédelmi tájékoztató.
- Felhasználási feltételek.

## 7.2. Ügyfélfelület

- Ügyfél vezérlőpult.
- Saját profil.
- Ajánlatkéréseim.
- Beérkezett ajánlatok.
- Foglalásaim.
- Üzeneteim.
- Kedvenceim.
- Értékeléseim.
- Értesítéseim.
- Beállítások.

## 7.3. Szolgáltatói felület

- Szolgáltatói vezérlőpult.
- Saját profil.
- Szolgáltatásaim.
- Referenciáim.
- Beérkezett ajánlatkérések.
- Elküldött ajánlatok.
- Foglalásaim.
- Naptár.
- Üzeneteim.
- Értékeléseim.
- Statisztikák.
- Ellenőrzési adataim.
- Előfizetésem.
- Beállítások.

## 7.4. Adminisztrációs felület

- Admin vezérlőpult.
- Felhasználók.
- Szolgáltatók.
- Ellenőrzési kérelmek.
- Kategóriák.
- Szolgáltatások.
- Ajánlatkérések.
- Foglalások.
- Értékelések.
- Bejelentések.
- Előfizetések.
- Rendszerbeállítások.
- Adminisztrátori napló.

---

# 8. Technológiai specifikáció

## 8.1. Frontend – Angular

A frontend Angular keretrendszerrel készül.

Az Angular feladata a felhasználói felület megjelenítése, a felhasználói interakciók kezelése és a backend API-val történő kommunikáció.

Használt technológiák:

- Angular.
- TypeScript.
- HTML5.
- SCSS.
- Bootstrap.
- Bootstrap Icons.
- Angular Router.
- Angular Forms.
- Angular HttpClient.

A frontend komponensalapú felépítést használ.

Tervezett főbb elemek:

- Közös navigációs sáv.
- Lábléc.
- Keresőkomponens.
- Kategóriakártyák.
- Szolgáltatói kártyák.
- Profilkomponensek.
- Űrlapok.
- Üzenetküldő komponens.
- Dashboard-komponensek.
- Adminisztrációs komponensek.

Az Angular Route Guardokkal történik a jogosultsághoz kötött oldalak védelme. A jogosultságokat azonban minden esetben a backendnek is ellenőriznie kell.

## 8.2. Backend – Node.js és Express.js

A backend Node.js futtatókörnyezetben, Express.js keretrendszerrel készül.

Feladata:

- API-végpontok biztosítása.
- Felhasználók kezelése.
- Hitelesítés és jogosultságkezelés.
- Adatbázis-kapcsolat.
- Szolgáltatások kezelése.
- Ajánlatkérések és ajánlatok kezelése.
- Foglalások kezelése.
- Üzenetek tárolása.
- Értékelések kezelése.
- Fájlok feltöltésének kezelése.
- Adminisztrációs műveletek kiszolgálása.

A backend rétegzett felépítést követ.

Javasolt mappastruktúra:

Backend/
- config/
- controllers/
- middleware/
- models/
- routes/
- services/
- validators/
- uploads/
- server.js

A route-ok kezelik a HTTP-kéréseket, a controllerek a műveletek vezérlését, a modellek pedig az adatbázis-műveleteket.

## 8.3. Adatbázis – MySQL

A platform MySQL relációs adatbázist használ.

Az adatbázis feladata a felhasználói adatok, szolgáltatások, ajánlatkérések, foglalások, üzenetek, értékelések és egyéb rendszeradatok tárolása.

Az adatbázis neve: `servibe`.

A táblák között elsődleges és idegen kulcsok biztosítják a kapcsolatokat.

## 8.4. REST API

Az Angular frontend REST API-n keresztül kommunikál a backenddel.

A kommunikáció JSON formátumban történik.

Tervezett API-végpontok:

| Terület | Példa végpont |
|---|---|
| Regisztráció | POST /api/auth/register |
| Bejelentkezés | POST /api/auth/login |
| Kijelentkezés | POST /api/auth/logout |
| Profil | GET /api/users/me |
| Profil módosítása | PATCH /api/users/me |
| Kategóriák | GET /api/categories |
| Szolgáltatások | GET /api/services |
| Szolgáltatás létrehozása | POST /api/services |
| Szolgáltatók keresése | GET /api/providers |
| Ajánlatkérés | POST /api/quote-requests |
| Ajánlatok | GET /api/offers |
| Ajánlat elfogadása | PATCH /api/offers/:id/accept |
| Foglalások | GET /api/bookings |
| Foglalás létrehozása | POST /api/bookings |
| Üzenetek | GET /api/conversations |
| Értékelések | POST /api/reviews |
| Értesítések | GET /api/notifications |
| Admin felhasználók | GET /api/admin/users |

A végpontok pontos kérés- és válaszformátumát a fejlesztés során API-dokumentációban is rögzíteni kell.

---

# 9. Adatbázis-tervezés

A következő táblák a rendszer tervezett adatmodelljét alkotják.

## 9.1. Alapvető táblák

**users**
- id
- username
- email
- password_hash
- full_name
- profile_image
- status
- created_at
- updated_at

**roles**
- id
- name

**user_roles**
- user_id
- role_id

A külön szerepkörtábla lehetővé teszi, hogy egy felhasználó egyszerre több szerepkörrel is rendelkezzen.

**provider_profiles**
- id
- user_id
- provider_name
- description
- provider_type
- phone
- address
- city
- county
- postal_code
- verification_status
- created_at
- updated_at

**provider_verifications**
- id
- provider_id
- document_type
- document_path
- status
- admin_note
- submitted_at
- reviewed_at

**categories**
- id
- parent_id
- name
- description
- image
- status

A parent_id segítségével alkategóriák is kialakíthatók.

**services**
- id
- provider_id
- category_id
- title
- description
- price
- pricing_type
- duration
- location_type
- status
- created_at
- updated_at

**service_locations**
- id
- service_id
- city
- county
- postal_code
- travel_radius

**portfolio_images**
- id
- provider_id
- image_path
- description
- created_at

**favorites**
- id
- user_id
- provider_id
- created_at

## 9.2. Ajánlatkérés és ajánlatok

**quote_requests**
- id
- customer_id
- category_id
- title
- description
- location
- desired_date
- budget_min
- budget_max
- status
- created_at

**quote_request_images**
- id
- quote_request_id
- image_path

**quote_request_providers**
- id
- quote_request_id
- provider_id

**offers**
- id
- quote_request_id
- provider_id
- price
- description
- duration
- valid_until
- status
- created_at
- updated_at

## 9.3. Foglalások és elérhetőség

**availability**
- id
- provider_id
- weekday
- start_time
- end_time
- is_available

**availability_exceptions**
- id
- provider_id
- date
- start_time
- end_time
- is_available

**bookings**
- id
- customer_id
- provider_id
- service_id
- offer_id
- booking_date
- start_time
- end_time
- location
- note
- status
- created_at
- updated_at

## 9.4. Kommunikáció

**conversations**
- id
- related_booking_id
- related_quote_request_id
- created_at

**conversation_members**
- conversation_id
- user_id

**messages**
- id
- conversation_id
- sender_id
- message
- is_read
- created_at

## 9.5. Értékelések és értesítések

**reviews**
- id
- booking_id
- customer_id
- provider_id
- rating
- comment
- provider_reply
- created_at
- updated_at

**notifications**
- id
- user_id
- title
- message
- type
- related_id
- is_read
- created_at

## 9.6. Adminisztráció és üzleti funkciók

**reports**
- id
- reporter_id
- reported_user_id
- related_review_id
- reason
- description
- status
- created_at

**subscription_plans**
- id
- name
- description
- price
- billing_period
- features
- status

**subscriptions**
- id
- provider_id
- plan_id
- status
- start_date
- end_date

**payments**
- id
- subscription_id
- amount
- currency
- status
- payment_provider
- transaction_reference
- created_at

**admin_logs**
- id
- admin_id
- action
- affected_entity
- affected_id
- created_at

A tényleges adatbázis létrehozásakor a mezők adattípusait, nullázhatóságát, alapértelmezett értékeit és kulcsait pontosan meg kell határozni.

A dokumentumok, képek és egyéb fájlok fizikai tartalmát nem közvetlenül az adatbázisban, hanem biztonságos fájltárolóban célszerű tárolni. Az adatbázis ezek elérési útját tartalmazza.

---

# 10. Nem funkcionális követelmények

## 10.1. Biztonság

A rendszernek védenie kell a felhasználói adatokat és a platform működését.

Követelmények:

- Jelszavak biztonságos hash-elése bcrypt vagy Argon2 használatával.
- Hitelesítés és jogosultságkezelés.
- Backendoldali jogosultság-ellenőrzés minden védett műveletnél.
- SQL injection elleni védelem paraméterezett lekérdezésekkel.
- XSS elleni védelem.
- CSRF elleni védelem, ha az alkalmazott hitelesítési megoldás ezt szükségessé teszi.
- Biztonságos fájlfeltöltés.
- Fájlméret- és fájltípus-korlátozás.
- Bejelentkezési próbálkozások korlátozása.
- HTTPS használata éles környezetben.
- Környezeti változók használata érzékeny adatokhoz.
- Adatbázis-biztonsági mentések.
- Adminisztrátori műveletek naplózása.

A hitelesítési megoldást úgy kell kialakítani, hogy a munkamenet vagy token biztonságosan legyen kezelve, és a hozzáférés szükség esetén visszavonható legyen.

## 10.2. Adatvédelem

A platformnak figyelembe kell vennie az Európai Unió általános adatvédelmi rendeletét (GDPR).

Követelmények:

- Adatkezelési tájékoztató.
- Felhasználási feltételek.
- Adatminimalizálás.
- Csak szükséges személyes adatok gyűjtése.
- Felhasználói adatok módosításának lehetősége.
- Fiók törlésének kezdeményezése.
- Dokumentumok korlátozott hozzáférése.
- Adatok biztonságos tárolása.
- Megfelelő adatmegőrzési szabályok.

A valódi kereskedelmi indulás előtt a jogi dokumentumokat és az adatkezelési folyamatokat szakértővel is ellenőriztetni kell.

## 10.3. Reszponzivitás

A webalkalmazásnak az alábbi eszközökön is megfelelően kell működnie:

- Asztali számítógép.
- Laptop.
- Tablet.
- Okostelefon.

A felhasználói felületnek különösen mobilon kell kényelmesen használhatónak lennie.

## 10.4. Felhasználóbarát kialakítás

- Egységes arculat.
- Átlátható navigáció.
- Logikus oldalszerkezet.
- Könnyen használható űrlapok.
- Érthető hibaüzenetek.
- Egyértelmű visszajelzések.
- Következetes gombok és ikonok.
- Olvasható betűméretek.
- Megfelelő kontraszt.

## 10.5. Teljesítmény

- Optimalizált képek.
- Lapozható találati listák.
- Adatbázis-indexek használata.
- Felesleges API-hívások csökkentése.
- Hatékony adatbázis-lekérdezések.
- Nagyobb listák fokozatos betöltése.
- Megfelelő hibakezelés.

---

# 11. Üzleti és bevételi modell

A ServiBe hosszú távon kereskedelmi szolgáltatásként is működhet.

A cél az, hogy a platform alapfunkciói az ügyfelek számára ingyenesen elérhetők legyenek, miközben a szolgáltatók különböző előfizetési csomagokkal további lehetőségekhez juthatnak.

## 11.1. Ingyenes csomag

Lehetséges funkciók:

- Alap szolgáltatói profil.
- Korlátozott számú szolgáltatás.
- Alap keresési megjelenés.
- Ajánlatkérések fogadása.
- Alapvető üzenetküldés.
- Értékelések kezelése.

## 11.2. Pro csomag

Lehetséges funkciók:

- Több szolgáltatás kezelése.
- Nagyobb referencia-képkeret.
- Részletes statisztikák.
- Kiemelt profilmegjelenés.
- Fejlettebb naptárfunkciók.
- További profiltestreszabási lehetőségek.

## 11.3. Business csomag

Elsősorban vállalkozásoknak:

- Céges profil.
- Több munkatárs kezelése.
- Több szolgáltatási terület.
- Haladó statisztikák.
- Több felhasználói hozzáférés.
- Ügyfélkezelési funkciók.
- Kiemelt megjelenési lehetőségek.

## 11.4. További bevételi lehetőségek

- Kiemelt szolgáltatói megjelenés.
- Hirdetési lehetőségek.
- Későbbi tranzakciós jutalék.
- Extra szolgáltatói funkciók.

A konkrét árakat a piac és a versenytársak vizsgálata után kell meghatározni.

A kezdeti időszakban célszerű ingyenes belépési lehetőséget biztosítani a szolgáltatók számára, hogy a platform megfelelő számú felhasználót és szolgáltatót tudjon elérni.

---

# 16. A projekt sikerességének feltételei

A ServiBe akkor tekinthető sikeresen megvalósított projektnek, ha:

- A felhasználók regisztrálhatnak és bejelentkezhetnek.
- A jogosultságok megfelelően működnek.
- A szolgáltatók saját profilt hozhatnak létre.
- A szolgáltatók kezelhetik saját szolgáltatásaikat.
- Az ügyfelek kereshetnek a szolgáltatók között.
- Az ügyfelek ajánlatkéréseket küldhetnek.
- A szolgáltatók ajánlatokat készíthetnek.
- Az ajánlatok elfogadása és elutasítása működik.
- Az időpontfoglalások kezelhetők.
- Az ügyfelek és szolgáltatók kommunikálhatnak.
- A teljesített szolgáltatások értékelhetők.
- Az adminisztrátor kezelheti a rendszer adatait.
- Az alkalmazás mobilon és számítógépen is használható.
- A rendszer megfelelő hibakezeléssel és alapvető biztonsági védelemmel rendelkezik.

---

# 17. Összegzés

A ServiBe egy komplex, magyarországi piacra tervezett szakemberkereső és szolgáltatáskezelő webalkalmazás.

A projekt célja, hogy a szolgáltatást kereső ügyfelek és a szolgáltatásokat kínáló szakemberek, vállalkozások és magánszemélyek számára közös, könnyen használható platformot biztosítson.

A rendszer a hagyományos szakemberkeresésen túl támogatja az ajánlatkérést, az ajánlatadást, az időpontfoglalást, a kommunikációt és az értékelést.

A fejlesztés Angular, TypeScript, Node.js, Express.js és MySQL technológiák felhasználásával történik.

A két fejlesztő közös GitHub repositoryban, egymással összehangolt munkafolyamatban dolgozik.

A hosszú távú elképzelés egy olyan megbízható szolgáltatói piactér létrehozása, amely Magyarországon valódi segítséget nyújt a mindennapi szolgáltatások megtalálásában és intézésében.
