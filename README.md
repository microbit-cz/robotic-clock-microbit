# Robotic clock with electronics stand
![App Screenshot](images/hodiny.jpg)
Project for a custom clock controlled by [microbit](https://microbit.org/)

## Languages
[![Language](https://img.shields.io/badge/Language-English-blue)](./README.md) [![Jazyk](https://img.shields.io/badge/Jazyk-Čeština-blue)](./README.cs.md)

## Potřebné věci před realizací
| Konkrétní položka  | Cena bez dopravy | Doprava |
| ------------- | ------------- | ------------- |
| [Překližka](https://www.cistedrevo.cz/dreveny-tacek-z-preklizky/)  | 19 kč | 69 kč |
| [4 dotykové senzory TTP223](https://aliexpress.com/item/32896003343.html) | 43,68 kč | 26,06 kč |
| [IR senzor TCRT5000](https://www.aliexpress.com/item/1005004150580253.html) | 14,03 kč | 26,06 kč |
| [Led kruh - WS2812B 24](https://www.aliexpress.com/item/4000183166176.html) | 75,30 kč |18,49 kč |
| [4× Led kruh - WS2812 5050 RGB LED lampa Panel 1/4](https://www.aliexpress.com/item/1005005161775410.html) | 189,8 kč | 23,17 kč |
| [Modulový drive servo motor pro arduino PCA9685](https://www.aliexpress.com /item/1005001621846654.html) | 69,39 kč | 5,57 kč |
| [RTC hodiny reálného času s paměťovým modulem pro Arduino DS3231](https://www.aliexpress.com/item/32822420722.html) | 10,92 kč | 11,36 kč |
| [KittenBot iobit V2.0 for micro:bit KBC9009A](https://www.aliexpress.com/item/32890235581.html) | 314,11 kč | zdarma |
| [Modul dvojitého H-můstku MX1508](https://www.aliexpress.com/item/1005001636421978.html) | 9,58 kč | 5,57 kč |
| [Mikrobit na ovládání hodin](https://www.aliexpress.com/item/1005005647468917.html) | 458,92 kč | 134,78 kč |
| [Led páska 4 adresovatelné kousky WS2812B](https://www.aliexpress.com/item/4001322411818.html) | 43,64 kč | 23,17 kč |
| [Filament na 3D tisk]
| [10× vrutů o průměru 3 mm](https://www.aliexpress.com/item/10000094157430.html)(varianta 3x10) | 10,92 kč | zdarma |
| [2× šrouby M 3×30](https://aliexpress.com/item/1005005469426695.html) | 23,07 kč | zdarma |
| [2× tavná matice](https://aliexpress.com/item/1005003582355741.html) | 14,93 kč | 44,78 kč |
## Burning
First, we start with burning into the plywood. The file [plywood](preklizka.sldprt), which we convert to a dxf file. This will contain the front and back planes. To make it easier for you, I've already put it into two files [front](Burnup/preglizkapredni123.dxf) and [back](Burnup/preglizkazadni123.dxf). The laser [atomstack x7](https://www.atomstack.eu/products/atomstack-x7-pro-50w-laser-engraver-and-cutter) was used. You need to find the center of the plywood and take into account the deviation of each plywood, because not every plywood is the same size. On our manufacturer's website the deviation is 2-5 mm. Clean with a brush after firing.
> **Warning**
> Constant checking is necessary during firing and it is forbidden to leave it unattended, as a fire may occur. I also recommend opening the windows in the room to reduce smoke accumulation.

## Printing
A 3D printer is "surprisingly" needed for printing. For this we used [prusa mini 2](https://www.prusa3d.com/cs/produkt/stavebnice-3d-tiskarny-original-prusa-mini-2/) and PLA filament was used. For example, we offered such a [filament](https://www.alza.cz/gembird-filament-pla-cerna-d4481219.htm). Of course you can choose the colour you want. You need to print all the parts you see in the picture. The printing time will take us about 12 hours. The weight is then determined by the filling. In our case it came out to about 152g.
![App Screenshot](images/PlastoveCasti.jpg)

### Konkrétní soubory na tisk
- [Motor box](ModelsSolidWorks/EngineBox.SLDPRT)
- [2× box for touch sensors](ModelsSolidWorks/BoxForTouchSensors.SLDPRT)
- [Hand](ModelsSolidWorks/HourHand.SLDPRT)
- [Stand](ModelsSolidWorks/Stand.SLDPRT)

## Component mounting
Basic mounting for the holder:
![App Screenshot](images/MainComponents.jpg)
Basic fitting for plywood:
![App Screenshot](images/SoucastkyNaPreklizku.jpg)
> **Warning**
> After buying the components, you need to check if they all work, especially for the touch sensors, if they can indicate touch.

## Final implementation
Install all the screws, in the necessary places and pull all the cables to the brackets. After implementation, label the IR sensor
## Price
The project cost us about 2000 (more precisely 1 995,28 CZK).
> **Note**
> The price is calculated in **06.06.2023**, so due to rising inflation, accounting for transport and geographical location, the price may vary significantly.
## Authors

- [@Jan Sebastián Kostlán](https://www.github.com/kostlanovec)
- [@Radek Janeček](https://www.github.com/RadekJanecek)
