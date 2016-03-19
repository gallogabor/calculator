###### Sorry for the hungarian only text! This project is made for Hungarian programmer students to let them learn something useful, so I don't think it's a must to provide the English version, too. And sorry for my poor English! :-)

# calculator
Egyszerű számológép alkalmazás, sok felesleges(nek tűnő) kiegészítéssel.

## Mi is ez?

Alapjában véve egy sima négyműveletes számológépnek indul a projekt. Viszont az összes elérendő cél megvalósítása miatt valószínűleg ennél több "tudása" lesz a végére, és biztosan lesznek olyan részei amit álmotokban sem gondolnátok bele egy számológépbe.

Persze sokkal kézenfekvőbb lenne egy névjegyzéket, szakácskönyvet, to-do listát vagy hasonlót csinálni adatbázisos vonalon... Remélem lesznek olyanok köztetek, aki ilyeneket készítenek az itt található források felhasználásával beadandónak!

Ezt a projektet kifejezetten az [EKF](http://uni-eger.hu/) 2015/16 tanévében másodéves PTI szakos hallgatók kedvéért készítem. Több kurzusra is kell beadandó szoftvert készítenünk, amikkel szemben különböző elvárásokat, követelményeket állítottak az oktatók.

Igyekszem itt összegyűjteni minden követelményt, és valamilyen működő megoldást mutatni rájuk egy projekt keretében. Nyilván emiatt sok erőltetett és felesleges része lesz a kész "rendszernek", de a kezdők érdekében próbálom az alap feladatot egyszerűnek megtartani, hogy könnyebb legyen az egészet megérteni, feldolgozni, felhasználni.

Nyilván lesznek benne kisebb-nagyobb hibák, esetleg ordas nagy tévedések. Ezeket kérem elnézni, és valamilyen formában jelezni!
Ha elvi/alapjaiban hibás bármelyik része, esetleg profibb módszer/megvalósítás is létezik, akkor nyilván szívesen veszem, ha bárki kisegít egy jobb megoldás kitalálásában, megvalósításában. Nem én tudom a legjobban! Sőt...

## Miért csinálom?

Azért döntöttem ezen publikus repó létrehozása mellett, mert sok tanácstalan arcot láttam az előadásokon a beadandókkal kapcsolatos elvárások sorolása közben.

Ezen felül némiképp elkeserít, hogy mennyire nem része a tananyagnak sok olyan témakör, ami a való életben hasznos lehetne egy kezdő (vagy akár haladó) programozónak. Ellenben tanulunk rengeteg olyan (jellemzően elméleti) anyagot, ami szép-jó és valóban illik ismerni, csak igazából soha sehová nem fog kelleni. Túl kevés az óraszám, és ennek túl nagy részét viszi el az ilyen (szerintem) haszontalan anyag. Pontosítok: nem haszontalan, csak mellettük nem marad idő valóban hasznos tudás átadására.

Szóval remélem ebből a projektből egy pár olyan dolgot is megtanulhatunk közösen, amire az iskolában nem jut idő.

## Mit tartalmaz?

A projektben a következőket tervezem megvalósítani, remélem mindet sikerül:
- Fejlesztési koncepciók
  * [x] Verzió kezelő rendszer (Source version control), Git haszálata (a GitHub-on vagyunk, így ez már sikerült is :-)
  * [ ] Tesztvezérelt fejleszési modell (TDD - Test Driven Development) használata
- Megvalósítandó célok
  * [ ] Több tervezési minta (design pattern) használata
  * [ ] Adatbázis kezelés
  * [ ] Dokumentációs (`///`) megjegyzések
  * [ ] Log-olás
  * [ ] Grafikus felhasználói felület (WPF lesz)
  * [ ] GUI és "üzleti" logika elkülönítése
  * [ ] WOW effektus (még nem tudom ezt mi adja majd...)

## Ki használhatja?

A repót bárki `clone`ozhatja, a saját példányban azt csinál amit csak akar. A GitHub-on lévő verziót egyenlőre csak én módosíthatom. Ha bárkinek saját ötlete van, bővítést, kiegészítést készítene, akkor írjon nekem, és megtárgyaljuk a hozzáférést. Ennek előfeltétele a [Git](https://git-scm.com/) ismerete és a [GitHub Flow](https://guides.github.com/introduction/flow/) elsajátítása (az újdonságokat `brach`-ben kell megvalósítani, amit egyenlőre én egyesítek a `master`-rel).

Javaslom a kód megértését, és utána történő felhasználását. Szerintem ha valakic csak `CTRL-C`, `CTRL-V` nyomkodással állítja innen össze a beadandóját (esetleg ezt viszi magával 1:1-ben, persze rajtam kívül), az nem lesz elég vizsga beugrónak...

## Mire van szükség a fejlesztéshez?

Egyenlőre csupán [Microsoft Visual Studio 2015 Community Edition](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) kell hozzá. Ami ezen felül szükséges, az vagy itt lesz a repóban, vagy kiegészítem ezt a leírást. A forrás (elvileg) olyan lesz, ami régebbi VS (és .NET) verziókkal is használható, viszont ha a fejlesztő rendszerrel kapcsolatban kérdez bárki (pl. hogyan kell a Git repót VS-ből kezelni), akkor csak a 2015-ös verzióban használható módszert tudom majd leírni.

Remélem hasznos lesz számunkra ez a (remélem közös) munka!
