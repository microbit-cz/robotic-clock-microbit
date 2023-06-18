# Robotické hodiny se stojanem na elektroniku
![App Screenshot](images/hodiny.jpg)
Projekt na vlastní hodiny ovládaný [mikrobitem](https://microbit.org/)

## Jazyky
[![Language](https://img.shields.io/badge/Language-English-blue)](./README.md) [![Jazyk](https://img.shields.io/badge/Jazyk-Čeština-blue)](./README.cs.md)

## Potřebné věci před realizací

- [Překližka](https://www.cistedrevo.cz/dreveny-tacek-z-preklizky/)
- [4 dotykové senzory TTP223](https://aliexpress.com/item/32896003343.html)
- [IR senzor TCRT5000](https://www.aliexpress.com/item/1005004150580253.html)
- [Led kruh WS2812B 24](https://dratek.cz/arduino/7693-rgb-led-kruh-24-x-neopixel-ws2812b.html)
- [Led kruh WS2812B 60](https://www.vokolo.cz/neopixel-ring/)
- [Modulový drive servo motor pro arduino PCA9685](https://www.aliexpress.com/item/1005001621846654.html)
- [RTC hodiny reálného času s paměťovým modulem pro Arduino DS3231](https://www.aliexpress.com/item/32822420722.html)
- [KittenBot iobit V2.0 for micro:bit KBC9009A](https://www.aliexpress.com/item/32890235581.html)
- [Modul dvojitého H-můstku MX1508](https://www.aliexpress.com/item/1005001636421978.html)
- [Mikrobit na ovládání hodin](https://www.aliexpress.com/item/1005005647468917.html)
- [Led páska 4 adresovatelné kousky WS2812B](https://www.aliexpress.com/item/4001322411818.html)
- [Filament na 3D tisk]
- [10× vrutů o průměru 3 mm](https://www.aliexpress.com/item/10000094157430.html)(varianta 3x10)
- [2× šrouby M 3×30](https://aliexpress.com/item/1005005469426695.html)
- [2× tavná matice](https://aliexpress.com/item/1005003582355741.html)

## Vypalování
Nejprve začneme s vypalováním do překližky. Soubor [preklizka](preklizka.sldprt), který převedeme do souboru dxf. Bude to obsahovat přední a zadní rovinu. Abych vám to ulehčil, tak jsem vám to již do dvou souboru [predni](Vypalovani/preklizkapredni123.DXF) a [zadni](Vypalovani/preklizkazadni123.dxf). Byl použit laser [atomstack x7](https://www.atomstack.eu/products/atomstack-x7-pro-50w-laser-engraver-and-cutter). Je potřeba si najít střed překližky a brát v potaz odchylku každé překližky, protože ne každá překližka je stejně velká. Na stránkách našeho výrobce je odchylka 2-5 mm. Po vypálení očištěte kartáčkem.
> **Warning**
> Při vypalování je nutná neustála kontrola a je zakázaný ocházet bez dozoru, jelikož může vzniknout požár. Taktéž doporučuji v místnosti otevřít okna pro snížení akumulace kouře

## Tisknutí
Na tisk je potřeba "překvapivě" 3D tiskárna. Na to jsme využili [prusa mini 2](https://www.prusa3d.com/cs/produkt/stavebnice-3d-tiskarny-original-prusa-mini-2/). Nabízí se nám třeba takový [filament](https://www.alza.cz/gembird-filament-pla-cerna-d4481219.htm). Samozřejmě barvu si vyberte jakou chcete. Je třeba vytisknout všechny části, kterou jsou na obrázku. Doba tisknu nám zabere cca 12 hodin. Podle vyplnění se pak odvíjí hmotnost. V našem případě to vycházelo na cca 152g.
![App Screenshot](images/PlastoveCasti.jpg)

### Konkrétní soubory na tisk
- [Krabička s motorem](motorkrabicka.SLDPRT)
- [2× krabička na pro dotykové senzory](ovladanikrabicka.SLDPRT)
- [Ručička](rucicka.SLDPRT)
- [Stojan](stojan-v6.SLDPRT)
#### Pro lepší manipulaci STL
- [Krabička s motorem](motorkrabicka.STL)
- [2× krabička na pro dotykové senzory](ovladanikrabicka.STL)
- [Ručička](rucicka.STL)
- [Stojan](stojan-v6.STL)

## Osazení součástek
Základní osazení pro držák:
![App Screenshot](images/MainComponents.jpg)
Základní osazení na překližku:
![App Screenshot](images/SoucastkyNaPreklizku.jpg)
> **Warning**
> Po nákupu součástek je potřeba zkontrolovat, zda všechny funují, hlavně u dotykových senzoru, jestli dokážou indikovat dotyk.

## Konečné realizování
Nainstalujte všechny vruty, na potřebná místa a natahejte všechny kabely k držáků. Po realizování naštilujte IR senzor
## Cena
Cca nás projekt vyšel na nějakých 2000 (přesněji 1 995,28 kč).
> **Note**
> Cena je počítána ve **06.06.2023**, takže kvůli rostoucí inflaci, započtení dopravy a geografické poloze se může cena podstatně lišit.
## Autoři

- [@Jan Sebastián Kostlán](https://www.github.com/kostlanovec)
- [@Radek Janeček](https://www.github.com/RadekJanecek)
