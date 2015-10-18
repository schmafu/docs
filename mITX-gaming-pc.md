# mini-ITX gaming pc

Nachdem ich mir einen 4k-Monitor zugelegt habe, benötige ich auch die passende Rechenpower dafür. Der 2012er Mac Mini ist auf  1440p beschränkt, aber generell ist zu hinterfragen, ob man mit einer Intel Onboard-Grafik einen modernen Desktop mit so hoher Auflösung betreiben will. Der 5k iMac wäre zwar nett, aber einerseits will ich nicht über ein Monatsgehalt für einen Stand-PC ausgeben, andererseits sind mir die Vorgaben von Apple zu rigide. Ich sehe ein, dass man bei einem Laptop auf Erweiterungsmöglichkeiten zugunsten kompakter Bauweise verzichtet. Abschließend könnte man noch anmerken, dass es einfach nur eine Kundenverarsche ist, wenn man in einem 2100 Euro Gerät standardmäßig eine Festplatte und keine SSD einbaut.

## Anforderungen

Die Must-Have-Kriterien:

* 4k über Displayport
* klein/kompakt
* leise
* aktuelle Spiele auf 1080p

Nice to Have:
* Linux Support
* Hackintosh-kompatibel
* aktuelle Spiele auf 4k

## Komponenten

# Gehäuse

Das Gehäuse ist für mich fast die wichtigste Entscheidung. Da es ein mITX-Build wird, steht es repräsentativ auf dem Tisch und verschwindet nicht wie ein herkömmlicher PC unter dem Tisch. Gut durchdachte und ästhetisch anspruchsvolle Lösungen findet man selten, anscheinend überlässt man dieses Feld komplett Apple. Da die Grafikkarte 2 Slots benötigt, reduziert sich das Bewerberfeld weiter. Lian Li überzeugen mich mit ihren dezenten Alu-Look. 

# Netzteil

Kleinere mITX-Gehäuse verwenden oft ein externes Netzteil, falls man keine Grafikkarte benötigt, sind diese sogar besser als die mit internen Netzteil. ein High-End-PC ohne Grafikkarte benötigt wahrscheinlich nur ein 120-160W Netzteil. Bei einer aktuellen High-End Grafikkarte wird es unter 500W nur einen schwarzen Bildschirm geben. Bei einem i3 und der GTX 960 ist wahrscheinlich ein 300W Netzteil schon Overkill. Aber es macht durchaus Sinn, ein überdimensioniertes zu kaufen, da diese bei wenig Last mit einer geringeren Lüfterdrehzahl kühlen. Da sich in einem mITX alles ziemlich staut, wäre ein vollmodulares Netzteil wünschenswert um den Kabelsalat zu reduzieren und so für mehr Luftzirkulation zu sorgen.

### CPU
AMD bietet mit den kombinierten CPU/GPU-Lösungen interessanten Alternativen, doch reichen diese nur für Low-End Gaming. Daher fällt die Wahl auf Intel, und hier muss man sich zwischen Quadcore und Dualcore entscheiden. Für den i3 spricht die niedrigere Abwärme, der höhere Takt und der Preis. Die wenigsten Spiele nutzen 4 Threads permanent gleichzeitig, in den Benchmarks schlägt sich die doppelte Anzahl an Kernen in einem moderaten Performancegewinn von 10% nieder.

### Mainboard

Nachdem man sich für die CPU entschieden hat, kann man sich ein passendes Mainboard aussuchen. Da nicht übertaktet wird, kann man eigentlich zum billigsten Board greifen. Ich wollte einen 4k Displayport und WLAN onboard, in dieser Kategorie war das MSI H97I am billigsten. Falls man Mac OS X aufsetzen will, sind die Boards von Gigabyte zu empfehlen. Für diese gibt es die meisten Patches in der Community.

### RAM
8 GB (egal von welcher Marke) sind für meine Zwecke ausreichend mehr als ausreichend. Der Aufpreis auf 16GB wäre zwar nicht teuer, aber dieses Argument gilt für fast alle Komponenten und dann summieren sich diese Einzelbeträge auf und am Schluss ist der PC fast doppelt so teuer.

### Grafikkarte

Jetzt wird es schwierig. Da ich ein mITX-Gehäuse verwende, darf die Kantelänge nicht 19cm überschreiten. Aktuelle Grafikkarten sind üblicherweise extrem lang. Auf Geizhals bleiben hier eine Handvoll über. Die Nvidia GTX 960 spricht mich am meisten an. Sie kostet knapp 200 Euro und ältere Spiele wie CS:GO und Diablo 3 lassen sich auf 4k mit hohen Details ca 45fps spielen. Der Stromverbrauch und somit die Abwärme halten sich auch in Grenzen.

### SSD

Eine SSD mit 512 GB sollten ausreichen, wem das zu wenig ist, könnte sich noch eine größere 2,5" Festplatte dazukaufen. Das LianLi-Gehäuse bietet Platz für 4 2,5" Laufwerke. 

## Liste

| Komponente  | Bezeichnung  | Preis in Euro |
|-------------|------------------|-------:|
| CPU         | [Intel Core i3 4170](http://geizhals.at/intel-core-i3-4170-bx80646i34170-a1250024.html?hloc=at) | 115 |
| Mainboard   | [MSI H97I](http://geizhals.at/msi-h97i-ac-7851-002r-a1111452.html?hloc=at) | 105 |
| RAM         | [DDR3-1600](http://geizhals.at/?cat=ramddr3&xf=5830_UDIMM1~253_8192~5828_DDR3~5831_DIMM~254_1600#xf_top) | 40 |
| Grafikkarte | [Gigabyte GTX 960](http://geizhals.at/gigabyte-geforce-gtx-960-windforce-2x-oc-gv-n960oc-4gd-a1288746.html) | 200 |
| SSD | [Crucial BX 100](http://geizhals.at/crucial-bx100-500gb-ct500bx100ssd1-a1215184.html?hloc=at) | 160 |
| Gehäuse | [Lian Li PC-Q01B](http://geizhals.at/lian-li-pc-q01b-schwarz-a1077884.html) | 60 |
| Netzteil | [be quiet Pure Power L8-430W](http://geizhals.at/be-quiet-pure-power-l8-cm-430w-atx-2-31-l8-cm-430w-bn180-a679523.html?hloc=at) | 60 |
|**Summe**| | **740** |

Falls man Mac OS X aufsetzen will, muss man zu einem i3 4**3**xx greifen. Ein Gigabyte-MB ist zwar nicht Pflicht, aber die Wahrscheinlichkeit steigt, dass dann unter Mac OS X alles _out of the box_ funktioniert.

Bei der Grafikkarte könnte man auch zu einer mITX-taugliche Variante des Preis/Leistungssiegers GTX 970 greifen, damit nähert man sich für rund 100 Euro Aufpreis der GTX 980 an, die die doppelte Performance der 960er liefert.

## Silent Mods

Da ich natürlich nicht mit den Standardkomponenten zufrieden bin, wird fleißig gemoddet. Vorne weg, F\*\*\* Y\*\* Asus! Die GTX 960 wird in den Reviews immer dafür gelobt, dass sich der Lüfter erst bei 60 Grad einschaltet. Nicht bei der mITX-Variante von Asus, dort dreht er auch im Leerlauf seine 1400 Umdrehungen pro Minute. Unter Volllast gleicht das Teil einer Turbine. Eigentlich hätte ich die Grafikkarte zurückschicken müssen, aber ich war mir nicht sicher, ob sich die Mini-Varianten der anderen Hersteller ähnlich verhalten. Also musste ein alternativer Lüfter drauf. 

### Arctic Accelero Mono Plus

Nach längerer Recherche bin ich beim [Arctic Accelero Mono Plus](http://geizhals.at/arctic-accelero-mono-plus-a691663.html?hloc=at) gelandet. Für 30 Euro ist er auf höchster Stufe leiser als der Asus im Leerlauf. Wer gerne herumschraubt und auf die Garantie der Grafikkarte verzichten kann, dem sei dieser Mod ans Herz gelegt. Ohne Gehäuselüfter und nach 2-3h zoggen bewegt sich die Temperatur der Grafikkarte bei 60 Grad. Bis 80 Grad wäre Spielraum. In den nächsten Tagen werde ich einen 5V Adapter einbauen. Aktuell wird der Lüfter mit 7V betrieben und ich glaube, dass es noch eine Spur leiser geht und sich die Temperatur weiter unter 70 Grad bewegen sollte.

Der Kühler nimmt 3 Slotstufen in Anspruch, beim mITX ist dies jedoch komplett egal, da nur 1 PCIe-Slot verbaut ist. Das Gehäuse bietet auch ausreichend Platz nach unten. Bei einem anderen Gehäuse muss man gegebenfalls abklären, ob man diesen Lüfter verbauen kann.

### Silvretta Alpenföhn

Bei der Namensgebung sind die Kühlerhersteller sehr kreativ. Ich betreibe aus Prinzip keinen PC mit dem Standard-CPU-Kühler, erfahrungsgemäß wird hier an allen Enden und Ecken gespart. Der [Silvretta Alpenföhn](http://geizhals.at/ekl-alpenfoehn-silvretta-84000000096-a949432.html) ist für kleine Gehäuse gedacht. Beim Lian Li Gehäuse befindet sich das Netzteil gegenüber von der CPU, d.h. man muss auf die Höhe des Kühlers aufpassen. Auf der niedrigsten Stufe ist der Lüfter aus normaler Entfernung nicht hörbar. Da kein Gehäuselüfter verbaut ist, muss schafft er es auf dieser Stufe nicht die CPU ausreichend zu kühlen. Dank Lüftersteuerung im BIOS(UEFI) kann ich die Grenzwerte selbst festlegen. Eine Intel-CPU kann man eigentlich nicht mehr grillen, daher erhöhe ich die Drehzahl erst bei 65 Grad.

## Fazit

Die großen PCs gehören der Vergangenheit an. SSDs und das Internet sorgten dafür, dass man keine Festplatten und optischen Laufwerke mehr benötigt. Durch die Integration von Funktionalität auf die CPU bzw. auf das Motherboard benötigt man eigentlich keine Erweiterungskarten mehr. In meinem ersten PC benötigte ich einen PCI-Slot für die Soundkarte, Netzwerkkarte und die Grafikkarte. Das ist nun alles hinfällig. Übrig geblieben ist die Grafikkarte und für den Alltagsbenutzer ist diese auch nicht mehr notwendig. Mit sorgsamer Komponentenauswahl und kleinen Umbauten kann man sich einen schreibtischtauglichen Silent-Gaming-PC zusammenstellen, der alle aktuellen Spiele in Full-HD bewältigt.

![Lian Li](http://geizhals.at/p/1077884.jpg)




