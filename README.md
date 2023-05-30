# zkzk

## Mobile environment characteristics
1) Omezené zobrazovací rozlišení: Mobilní zařízení mají menší displeje a nižší zobrazovací
rozlišení než desktopové monitory. Vyžaduje se optimalizace uživatelského rozhraní a
přizpůsobení obsahu pro menší obrazovky.
2) Omezený výkon: Mobilní zařízení mají nižší výkon než desktopové počítače. Omezený
výkon procesoru, paměti a grafických schopností ovlivňuje rychlost a výkon mobilních
aplikací. Je nutné optimalizovat kód aplikace pro efektivní provoz.
3) Omezená paměť: Mobilní zařízení mají omezené množství paměti ve srovnání s
desktopovými počítači. Je třeba optimalizovat využití paměti a minimalizovat paměťové
nároky aplikace.
4) Omezená konektivita: Mobilní zařízení často používají mobilní sítě s omezenou šířkou
pásma a nestabilním připojením. Mobilní aplikace musí být schopna pracovat v omezených
síťových podmínkách a správně zpracovávat přerušená nebo pomalá připojení.
5) Různé vstupní metody: Mobilní zařízení podporují různé vstupní metody, jako je dotykové
ovládání, gesta, akcelerometry, gyroskopy a další senzory. Mobilní aplikace musí být
navrženy s ohledem na tyto různé vstupní metody.
6) Mobilní kontext: Mobilní zařízení se používají na pohyb a v různých prostředích. Mobilní
aplikace musí zohledňovat mobilní kontext, jako je poloha uživatele, pohyb, osvětlení atd.
Tyto informace lze využít k poskytování personalizovaných funkcí a zlepšení uživatelského
zážitku.
7) Integrované funkce: Mobilní zařízení disponují kamerami, GPS, akcelerometry a dalšími
senzory, které umožňují rozšířené možnosti interakce. Mobilní aplikace je mohou využívat
pro fotografování, videonahrávání, určování polohy, detekci pohybu a další účely. Tyto
funkce vyžadují přizpůsobení návrhu.

## Usability testing. Early phase
Testování použitelnosti (usability testing) v ranní fázi vývoje aplikace se obvykle zaměřuje na
testování lo-fi prototypu, který je vytvořen na základě původního návrhu aplikace. Cílem
testování je ověřit, jak dobře uživatelé rozumí a zvládají interakci s prototypem aplikace.
Testy se snaží zjistit, jak efektivně uživatelé splňují úkoly, jak snadno se orientují v aplikaci, s
jakými problémy se setkávají při používání, a jaké jsou jejich obecné dojmy a zkušenosti. Při
testování použitelnosti v ranní fázi je důležité dávat pozor na následující aspekty:
- Jasná definice cílů testování: Je třeba mít jasně stanovené cíle a otázky, na které se
chceme zaměřit při testování.
- Výběr vhodných uživatelů: Vybraní uživatelé by měli odpovídat cílové skupině, pro
kterou je aplikace určena.
- Příprava a provedení testů: Testy by měly být pečlivě připraveny a strukturované tak,
aby uživatelé měli jasný úkol a aby bylo možné shromáždit konkrétní a užitečné
informace. Testování by mělo být provedeno v kontrolovaném prostředí, které
simuluje skutečné používání aplikace.
- Sledování a zaznamenávání výsledků: Během testování je důležité pečlivě sledovat
reakce uživatelů, zaznamenávat jejich připomínky, potíže a pozorování. Získané
výsledky a zpětná vazba jsou cennými informacemi pro vylepšení a vývoj aplikace.
- Otevřenost pro změny a vylepšení: Testování použitelnosti v ranní fázi je příležitostí
identifikovat slabá místa a potenciální problémy v návrhu aplikace, přispívá k
identifikaci nedostatků a zlepšení uživatelského zážitku. Pomáhá zajistit, že aplikace
je intuitivní, snadno použitelná a efektivní pro uživatele.

## Mechanismus seskupování. Popište mechanismy použité na obrázku
- Zmenšení bílého místa:
  - na základě textu
    - zhuštěná písma,
    - velikost písma změna struktury textu (např. odstranění zalomení řádků)
  - grafické
    - přepracování designu
- Zmenšení obsahové části:
  - na základě textu
    - shrnutí klíčová slova,
    - zobrazit/skrýt
  - na grafickém základě
    - techniky zvětšování
    - techniky zaměřování a kontextu
- Snížení zabírání místa ovládacími prvky uživatelského rozhraní <br>

Zmenšení obsahové části pomocí:
- Collapsible blocks umožňují uživatelům rozbalovat nebo sbalovat části
informací podle jejich zájmů nebo potřeb
- Pagination používaná k rozdělení velkých souborů informací na menší,
snadno zvládnutelné části. Rozdělením obsahu na více stránek nebo
obrazovek mohou uživatelé informace snadněji procházet.
- Menu uspořádání a prezentace informací. Poskytují navigační strukturu, která
uživatelům umožňuje přístup k různým sekcím nebo funkcím aplikace
- Tabs seskupování souvisejících informací do samostatných oddílů nebo
kategorií. Uživatelé mohou mezi tabami přepínat a přistupovat tak k různým
souborům informací.
- Dashboard centralizované a přizpůsobitelné zobrazení, které stručně a
přístupně prezentuje klíčové informace, metriky a vizualizace. Uživatelům
poskytuje přehled relevantních dat a poznatků a umožňuje jim sledovat a
analyzovat informace na první pohled.

## Obrazovka email
- Tap – otevřít side menu, otevřít zprávy a napsat novou zprávu, přidat do oblíbených, hledání.
- Tap and hold – vybrat jednu nebo několik zpráv smazat je nebo označit jako přečtené.
- Vertical swipe – listování zpráv.
- Horizontal swipe – mazání zpráv

## Telefon a barvy
Tento obrázek znázorňuje dosažitelnost prstu k určitým oblastem telefonu. Zelená oblast
znamená, že uživatel bez úsilí schopen dosáhnout tam prstem. Žlutá oblast znamená, že
prst tam může dosáhnout, ale je potřeba trochu úsilí. Červená oblast je nedosažitelná a
vyžaduje, aby uživatel změnil polohu rukou nebo použil druhou. Při vytváření aplikace bude
vývojář vědět, že je nejlepší umístit navigaci dolů, protože je v zelené oblasti a vyžaduje více
interakcí s uživatelem. Tlačítko pro vyhledávání může být umístěno nahoře, protože ho
uživatel příliš často nepoužívá. Tlačítka jako tlačítko zpět jsou také umístěna nahoře v
aplikaci, aby uživatel při aktivním používání aplikace nezmačknul ho omylem.
Alternativní způsoby držení telefonu v rukou:
- Jednou rukou (first/second order),
- Dvěma rukama (portrait/landscape),
- Hold and touch
- Cradled

## Popište, k jaké úpravě uživatelského rozhraní došlo
Nejprve jsme přesunuli prvky z list grid do bottom navbar, což zjednodušilo design aplikace a
uživatelům usnadnilo orientaci mezi stránkami. Také vidím, že jsme spojili stránku s mapou a
stránku s fotografiemi, což skutečně zlepšilo sledování aplikace a uživatelům umožnilo
pohodlně přepínat mezi způsoby zobrazení (což často používají). Celkově se zlepšilo ux, a
ikonky SVG vypadají minimalisticky.
Výhody:
- Vidíme důležitou informaci hned po otevření aplikace.
- Pohodlná navigace mezi stránkami, bottom navbar se nachází v snadno dosažitelné zóně.
- Minimalismus.

## Gesty mapa
- Swipe any direction – měnit pozice mapy.
- Spread/pinch – měnit velikost mapy.
- Rotate with two fingers – měnit orientace mapy.
- Tap – hledání, otevřít side menu, interakce s bottom navbar a floating button, změna druhu
mapy, zobrazí se informace o místě (pokud má značku), na který byl dotyk.
- Tap and hold – zobrazí souřadnice dané polohy.

## Design guidelines
Design guidelines jsou soubor doporučení a pravidel, která slouží jako referenční materiál
pro tvorbu konzistentního a přívětivého UI nebo UX. Jejich hlavním cílem je poskytnout
designérům a vývojářům jasný rámec pro vytváření produktů, které splňují uživatelské
potřeby, očekávání a ergonomické standardy. Obsahuje různé hotové komponenty, vizuální
prvky(barvy, typografie, ikony), interakční pokyny(chování prvku, animace), rozložení na
obrázovce. Existuje pro platfomy android(Material design), microsoft(Fluent), iOS a pro další
platformy

## Fused location provider
Fused location provider je technika využívaná v mobilních zařízeních pro přesné a
spolehlivé získávání informací o poloze uživatele. Při použití tohoto přístupu jsou
kombinovány data z různých senzorů a zdrojů polohy, což vede k vylepšené přesnosti a
spolehlivosti výsledků. Sekvence, jak probíhá optimalizované určování polohy, může být
následující:
1. Získání dat z GPS: Nejprve se zařízení pokusí získat polohu pomocí GPS (Global
Positioning System). GPS senzor využívá signály ze satelitů pro přesné určení
polohy. Pokud je signál dostatečně silný a dostupný, GPS poskytuje nejpřesnější
informace o poloze, ale je pomalý.
2. Využití dat z Wi-Fi: Pokud není signál GPS dostatečně silný nebo nejsou k dispozici
dostatečné satelity, zařízení může využít síť Wi-Fi pro získání informací o poloze.
Wi-Fi přístupové body jsou přiřazeny k určitým polohám, a proto se pomocí něj dá
přibližně určit polohu zařízení.
3. Využití dat z mobilní sítě: Pokud nejsou k dispozici ani silné GPS signály ani
dostatečné množství Wifi přístupových bodů, zařízení může využít informace z
mobilní sítě, ale poloha bude určena nepřesně. Tato data zahrnují informace o
přípojném bodu, mobilní věže a další dostupné signály pro aproximaci polohy.
4. Fusion a optimalizace dat: Poté, co jsou získána data z různých senzorů a zdrojů
polohy, probíhá proces fúze a optimalizace těchto dat. To zahrnuje kombinaci a
vyhodnocování informací z různých zdrojů s cílem poskytnout nejpřesnější možnou
polohu

## Test usability. Later phase
Testování použitelnosti v pozdější fázi vývoje aplikace se zaměřuje na ověření, zda je
aplikace snadno použitelná a splňuje potřeby uživatelů. Tento typ testování se provádí s
reálnými uživateli aplikace a je často provedený na hi-fi prototypu nebo na finální verzi
aplikace. <br>
Testy použitelnosti se snaží ověřit několik klíčových aspektů:
- Efektivita: Zjišťuje se, zda uživatelé dokážou efektivně plnit své úkoly pomocí
aplikace a zda dosahují požadovaných výsledků.
- Efektivnost: Testuje se, jak rychle uživatelé dokážou splnit úkoly pomocí aplikace a
kolik úsilí musí vynaložit.
- Spokojenost: Hodnotí se, zda jsou uživatelé spokojeni s celkovým uživatelským
zážitkem, designem, funkčností a přívětivostí aplikace.
- Chybovost: Zjišťuje se, jak často se uživatelé dopouštějí chyb při používání aplikace
a jaké jsou důsledky těchto chyb. <br>

Testování použitelnosti může probíhat v různých prostředích, v závislosti na cílové skupině
uživatelů a kontextu použití aplikace. Může se jednat o laboratorní prostředí, kde jsou
vytvořeny simulované scénáře, nebo o prostředí reálného používání aplikace, například ve
firemním prostředí, domácím prostředí nebo na veřejnosti. <br>
Při přípravě testu a procesu analýzy je důležité věnovat pozornost několika aspektům:
- Definice cílové skupiny: Je nezbytné určit, kdo jsou cíloví uživatelé aplikace, aby se
zajistilo, že testování bude relevantní a získané výsledky budou použitelné pro
vylepšení aplikace.
- Definice úkolů: Je důležité jasně definovat úkoly, které budou uživatelé plnit během
testování. Úkoly by měly být reprezentativní pro typické scénáře použití aplikace.
- Správný výběr metrik: Je vhodné vybrat vhodné metriky a nástroje pro sběr dat, které
odpovídají cílům testování. To může zahrnovat čas potřebný na splnění úkolů,
úspěšnost úkolů, spokojenost uživatelů nebo počet chyb.
- Kvalitní analýza dat: Při analýze dat je důležité věnovat pozornost statistickému
zpracování výsledků a vyvozování smysluplných závěrů. Získané poznatky by měly
sloužit k identifikaci problémů v aplikaci a navržení vhodných řešení.
