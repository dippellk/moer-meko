---
title: A03 - Verortung und Messung räumlicher Phänomene
toc: true
header:
  image: /assets/images/02-splash.jpg
  image_description: "Blick ins Lahntal mit Grünlandwirtschaft, Baustelle für Stromtrassen und Regenbogen."
  caption: "Foto: T. Nauss / CC0"
---


Sie haben bereits die Bedeutung der Modellierung für die räumliche Perspektive auf die Welt kennengelernt. In der vorherigen Einheit wurden Räume eingegrenzt und innerhalb der Eingrenzung Charakteristika abstrahiert. Diese haben Sie beschrieben und in Skizzen festgehalten. Für eine präzise Kommunikation und Analyse von räumlichen Phänomenen ist es notwendig diese Abstraktion zum einen an Konventionen anzuschließen und zum anderen durch mathematische Abbildungen zu präzisieren.

### Der Ort

Um räumlich zu messen, Eigenschaften räumlich zu vergleichen oder auch nur die Merkmale spezifischer Objekte geographisch darzustellen, müssen beliebige Objekte exakt verortet oder georeferenziert werden. Es gibt eine Reihe von ähnlichen Ausdrücken für diesen Vorgang, wir sprechen vom Georeferenzieren, Geolozieren, Verorten oder ganz modern vom Geotagging. Allen Begriffen ist gemeinsam, dass Merkmalsausprägungen an geographisch identifizierbare und kartographisch abbildbare Positionen gebunden werden.

### Namen und Adressen

Orte durch Benennung und Beschreibung identifizieren und lokalisieren zu können gehört zu den ältesten Kulturtechniken der Menschheit. 

 Die Kombination von Namen und Ziffern, Deutschhaustrasse 10 in 35032 Marburg ist die postalische Kodierung für das Gebäude des Fachbereichs Geographie in Marburg. Auch wenn nicht alle Menschen eine auf diese Weise verschlüsselte Raumposition entschlüsseln können, gibt es ein weltweites Netz von Experten, die mit Hilfe dieser Kodierung einen Brief des Reisebüro Maluti Travel & Tours in Maseru, Lesotho zum Deutschen Haus in Marburg transportieren können. Umgekehrt gibt die Kodierung Maluti Travel & Tours, POB 14889, 0100 LNDL Building, Kingsway, Maseru Lesotho die Raumposition dieses Reisebüros an. Vielleicht kennen Sie aus Interesse oder Zufall die geographisch kodierte Position des Deutschhauses in Marburg, die Positionsangaben des LNDL Building in Maseru kennen Sie jedoch mit an Sicherheit grenzender Wahrscheinlichkeit nicht. Wiederum kennt auch der Postbote sicher nicht die geographischen Koordinaten der Empfängerorte, die er tagtäglich bedient – dennoch kommt die Post (meist) zuverlässig an ihrem Bestimmungsort an.

Das räumliche Referenzierungssystem hierfür funktioniert anders als über geographische Koordinaten, nämlich über Namen. Es ist eine Kette von Namenskodierung vom Nationalstaat über die Region bis hin zum Gebäude. Wenn sich dieser Name ändert, wie beispielsweise von Karl-Marx-Stadt in Chemnitz, bleibt selbstredend der geographische Raumbezug erhalten. Natürlich gibt es Ortsnamen, die vielfach vorkommen, so z.B. London oder Neunkirchen. Eine eindeutige Referenzierung nach dem vorgestellten System ist nur dann möglich, wenn der Ortsname eindeutig durch ein übergeordnetes Zuordnungssystem identifiziert werden konnte. Die wichtigste Schlussfolgerung ist, dass in GI-Systemen zur Vermeidung von Redundanzen, Fehlern und Unsicherheiten zur Referenzierung unbedingt ein möglichst allgemeingültiges, zweckdienliches System verwendet werden sollte (deshalb hat die Thurn und Taxis Post 1853 in Deutschland Ortsnamen mit einem Zahlenschlüssel kodiert, der eine abstrakte, nachvollziehbare Identifikation der Raumposition dieser Orte möglich macht).


**Allen geographischen Informationen liegt eine eindeutige räumliche Zuordnung zugrunde.**

### Metrische Verortung

Ein System der systematischen Identifikation geographischer Orte haben wir mit den Postleitzahlen bereits kennen gelernt. Stellen wir uns nun folgenden Sachverhalt vor (Abb. 03-04):

<html><a href="https://www.flickr.com/photos/environmentalinformatics-marburg/13981635311" title="03-4 by Environmental Informatics Marburg, on Flickr"><img src="https://farm8.staticflickr.com/7325/13981635311_ae1b12e0cf.jpg" width="500" height="257" alt="03-4"></a></html>

**Abbildung 03-04: Pannenort nördlich von Holtau (GIS.MA2009)**

Während der Zustellung des Briefes in Flensburg bleibt der Post-LKW auf der Bundesautobahn 7 liegen. Mit seinem mobilen Telefon steckt der Fahrer gerade im Funkloch und muss (natürlich nach Absicherung der Pannenstelle) zu Fuß zu einer Meldesäule. Auf seinem Weg läuft er an einem kleinen blauen Schild vorbei, auf dem 64,0 zu lesen ist. Angekommen an der Meldesäule gibt er seine Panne bekannt, gibt die Auskunft, dass sich das Pannenfahrzeug kurz hinter Kilometer 64,0 in Fahrtrichtung Nord hinter der Anschlussstelle Soltau befindet und die rechte Fahrspur blockiert. Wenig später hören Sie im Verkehrsfunk:


“1,5 km Stau zwischen der Anschlussstelle Soltau und der Anschlussstelle Bispingen wegen eines defekten LKW. Die rechte Fahrspur ist blockiert. Bitte fahren Sie vorsichtig”

Dieses alltägliche Beispiel verdeutlicht die Kombination aus Namen und metrischer eindimensionaler Positionsangabe als geographischem Verortungssystem. Da Sie die Autobahn unterwegs nicht verlassen können orientieren Sie sich von Ausfahrt zur Ausfahrt (Namen oder Ausfahrtskennziffer). Ihnen genügt daher die Information des Verkehrsfunks für eine ausreichend genauen Verortung des Staus.

Der Polizei oder dem Pannendienst genügt diese Angabe nicht. Sie hätten gerne z.B. zur Organisation der Bergung bzw. zur Einschätzung der Gefahren die Kilometerangabe. Die Kilometrierung ist eine metrische Ortsangabe, die nur eine Dimension benötigt, da sie auf einer eindeutig definierten Strecke angeordnet ist. Ein solches Verortungskonzept ist metrisch also quantitativ. Es misst von einem definierten Ursprung/Start die Entfernung bis zum Zielpunkt/-ort. Diese sogenannte lineare Referenzierung kann nur auf eindimensionale Geoobjekte Anwendung finden. Von diesen gibt es eine Vielzahl in unserem Alltag. Angefangen bei Autobahnen oder Gleisanlagen bis hin zu Rohr- und Versorgungsleitungen sind alle linearen, als Netzwerke ausgeprägten Strukturen linear referenzierbar.

**Lineare Referenzen sind immer topologisch korrekt und können immer in geometrisch eindimensional messbaren Entfernungen angeben werden.**

#### Geometrisch exakte maßstäbliche Raumabbildung

Im vorausgegangen Kapitel haben wir die eindimensionale metrische Referenzierung kennengelernt. Als zweidimensionale Erweiterung gibt es weltweit sogenannte Kataster. Es ist üblich, dass Kataster in Katasterplan und Katasterbuch unterschieden werden (Abb. 03-06). In Deutschland ist (wie in den meisten Ländern) die Führung und Pflege hoheitlich durch Vermessungsämter geregelt.

<html><a href="http://upload.wikimedia.org/wikipedia/commons/8/84/Bukowsko_-_mapa_katastralna_%281906%29.jpg" title="03-5 by Environmental Informatics Marburg, on Flickr"><img src="http://upload.wikimedia.org/wikipedia/commons/8/84/Bukowsko_-_mapa_katastralna_%281906%29.jpg" width="500" height="348" alt="03-5"></a></html>

**Abbildung 03-06: Historischer Katasterplan von Bukowsko, Galizien (Silarski 2009)**

Dies liegt in der Notwendigkeit eines rechtskräftigen Nachweis von Eigentumsrechten (bekanntermaßen ein heikles Thema) begründet. Kataster bestehen seit der Antike für den persönlichen Nachweis von Steuerpflicht auf das Eignen von Liegenschaften. In den Kopfsteuerverzeichnissen wird an eine Person gebunden, die Steuerpflicht, bezogen auf Vermögen oder Liegenschaften, namentlich beschrieben.

Seit der Erfindung und Durchführung der exakten Vermessung der Welt durch Carl Friedrich Gauß (1777 – 1855) werden Kataster als flächendeckende Beschreibungen aller Flurstücke eines Landes durchgeführt. Für Deutschland wurde dies rechtlich durch den Code Civil Napoleons eingeführt und vom preußischen Staat vorbildlich umgesetzt. Der Kataster ist aufgeteilt in einen beschreibenden Teil – das sogenannte Liegenschaftsbuch – und in einen graphischen Kartenteil, die Liegenschaftskarte. In Beiden werden die geometrische Lage, die baulichen Anlagen, die Liegenschaften und die Art der Nutzung und Größe beschrieben sowie die Eigentumsverhältnisse und Rechtslasten festgelegt. Die Abbildung des Katasterplans stellt einen solchen graphischen Plan exemplarisch dar. Betrachtet man diese Abbildung genauer wird das Wort Plan verständlich. Die Parzellen sind zwar geometrisch exakt abgebildet, jedoch fehlt jegliches geographisches Referenzsystem. Vielmehr kann man eine Reihe von Ziffern für jede abgebildete Fläche identifizieren. Diese Ziffern verweisen auf die zugehörigen Eintragungen im Grundbuch. Analog zur linearen Referenzierung, die eindimensionale Geoobjekte metrisch referenziert, wird bei Katastern eine zweidimensionale metrische Referenzierung vorgenommen.

**Katasterpläne sind immer topologisch korrekt und bieten immer geometrisch zweidimensional maßstäblich messbare Entfernungen und Flächen.**

## Raum in geographischen Informationssystemen

Der Raum in GI-Systemen wird in Anlehnung an die Mathematik und Physik als dreidimensionaler euklidischer Raum verstanden. Aus dem Mathematikunterricht kennen wir die euklidische Ebene (mit 2 Dimensionen) und den euklidischen Raum (mit 3 Dimensionen). Am einfachsten kann der euklidische Raum mit Hilfe eines kartesischen Koordinatensystems beschrieben werden, in dem die Koordinaten entlang senkrecht aufeinander stehender Achsen abgetragen sind (vgl. Abb. 02-1)

<html>
 <a  href="http://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Cartesian-coordinate-system.svg/354px-Cartesian-coordinate-system.svg.png" title=""><img src="http://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Cartesian-coordinate-system.svg/354px-Cartesian-coordinate-system.svg.png" width="50%"  alt="01-08-Geoobjekt-schema1"></a>
</html>
*Abbildung 02-01: Ausschnitt aus einem zweidimensionalen kartesischen Koordinatensystem mit 3 eingetragenen Punkten in Koordinatenschreibweise (Bolino 2008)*

<html>
 <a  href="http://upload.wikimedia.org/wikipedia/commons/thumb/2/2c/3D_coordinate_system.svg/487px-3D_coordinate_system.svg.png" title=""><img src="http://upload.wikimedia.org/wikipedia/commons/thumb/2/2c/3D_coordinate_system.svg/487px-3D_coordinate_system.svg.png" width="50%"  alt="01-08-Geoobjekt-schema1"></a>
</html>
*Abbildung 02-2: Allgemeine Abbildung eines dreidimensionales kartesischen Koordinatensystem mit euklidischen Ebenen durch den Ursprungspunkt (Sakurambo 2007)*



### Die Raumrichtungen

Mit Hilfe einer Koordinate (x- und y-Wert) kann im zweidimensionalen Raum die Position eines Punktes eindeutig festgelegt werden. In der Regel spielt auch die Höhe des Punktes, im Sinne von z. B. der Höhe über dem Meeresspiegel oder der Höhe über der Erdoberfläche, eine Rolle. Hierfür muss folglich auch die dritte Raumdimension (z-Wert) berücksichtigt werden (vgl. Abb. 02-2).

Wenn ein Geoobjekt durch einen Punkt repräsentiert wird, dann ist für eine eindeutige Verortung ein Punkt (x, y, z) im dreidimensionalen Raum ausreichend. Oft haben die in Karten oder GI-Systemen repräsentierten Geoobjekte aber auch selbst eine mehrdimensionale Ausbildung. Dabei versteht man unter der Dimension eines Geoobjektes die voneinander unabhängigen Raumrichtungen, die zur Repräsentation des Geoobjekts verwendet werden (vgl. Abb. 02-3). Diese korrespondieren mit den geometrischen Eigenschaften von Punkten, Strecken, Flächen und Körpern in einem kartesischen Koordinatensystem:
  * 0D Geoobjekte: Punkte (Orte); keine Länge und Fläche (z.B. Messstation, Bohrpunkt)
  * 1D Geoobjekte: Strecken; definiert durch eine Länge aber keine Fläche (Gewässerlängsprofil, vertikales Bodenprofil)
  * 2D Geoobjekte: Flächen; definieren einen geschlossenen Linienzug (Sportplatz,  Stadtgebiet, Einzugsgebiet)
  * 3D Geoobjekte: Körper; werden z. B. als Volumen-Körper (Solide) oder Grenzflächen-Körper (Polyeder) definiert (Grundwasserkörper, Atmosphäre).

<html>
<a href="https://www.flickr.com/photos/environmentalinformatics-marburg/13970512442" title="02-3 by Environmental Informatics Marburg, on Flickr"><img src="https://farm8.staticflickr.com/7087/13970512442_289d700fb6.jpg" width="500" height="122" alt="02-3"></a>
</html>

*Abbildung 02-03: Dimensionalität von Geoobjekten (verändert nach Bartelme 2005)*

Neben den räumlichen Merkmalen sind Geoobjekte durch weitere Eigenschaften charakterisiert (z. B. kann einem Fluss ein Name zugeordnet sein, einer Stadt die Einwohnerzahl etc.). Diese, nicht die räumliche Geometrie betreffenden Merkmale eines Geoobjektes, werden als Attribute bezeichnet und bilden die thematische Dimension. Die zeitliche Veränderung von Geoobjekten oder Systemen wird in der Regel 4. Dimension genannt.

<!--
http://www.youtube.com/v/zX2EcvzsmcE?.swf?400×333
-->

### Was sind geographische Daten?

Trotz der bisherigen Erläuterungen ist die Beantwortung der Frage „Was sind geographische oder Geodaten?“ nicht ganz einfach. Auch wenn die im Film gezeigte Umfrage kaum repräsentativ sein dürfte, scheinen Laien nur eine schwach ausgeprägte Vorstellung von dem Begriff Geodatum zu haben.

Geodaten oder geographische Daten (singl. Datum) liefern räumlich fixierte, maschinenlesbare Konstrukte aus Zeichen, Bildern oder Funktionen die mit entsprechenden Interpretationsregeln zu Informationen werden. Da Daten Interpretationsvorschriften benötigen, um zu Informationen zu werden, müssen wir dieses Wissen nur noch mit dem Ziel, eine geographische Repräsentation der Welt durchzuführen, verbinden.

Die zentrale Fragestellung lautet: Was ist spezifisch geographisch und wie können wir diese geographische Ableitungen der Wirklichkeit durchführen? Ein typisches Beispiel für Geodaten ist in folgender Aussage kodiert:

“Die Temperatur am Havanna Airport betrug am Donnerstag, den 17.09.2009 um 08:00 lokaler Zeit 23.0°C. Die Koordinaten lauten: 22° 59' 21'' N, 82° 24' 33'' W, 64 m ü. MSL.”

Analysieren wir diese Aussage so finden wir alle wesentlichen Elemente der geographischen Repräsentation eines Echtweltobjekts. Die Aussage verbindet Raum (Koordinaten und Höhe) mit Zeit (Datum/Zeitangabe) und der Eigenschaft bzw. dem Attribut der Lufttemperatur. Zusätzlich sind dem derart festgelegten Ort weitere Eigenschaften zugeordnet: Havanna und Airport. Aus dieser Aussage kann schließlich folgendes geographisches Datum gebildet werden:

22° 59' 21'' N; 82° 24' 33'' W; 64 m ü. MSL; 8.00 Uhr LT; Havanna Airport; 23.0 °C

Geographische Daten verbinden somit räumlich eindeutig verortete Objekte mit mindestens einer Merkmalsausprägung. Diese „Daten-Primitive“ können natürlich beliebig komplex werden und darüber hinaus direkt oder auch indirekt zueinander in Beziehung gesetzt bzw. voneinander abgeleitet werden. Auch scheinbar nicht geographische Aussagen wie:

„Der K2 hat den schwersten Normalweg eines 8000er Gipfels“

können in ein geographisches Datum überführt werden. Hierzu sind weitere Kenntnisse bzw. Dekodierungsvorschriften notwendig. So muss man wissen dass K2 der international bekanntere Namen des Lambha Pahar, des zweithöchsten Berges der Erde ist. Weiterhin muss bekannt sein, welche geographischen Koordinaten seinen Gipfel repräsentieren und dass „Normalweg“ im Alpinistenjargon der „am häufigsten begangene und in der Regel einfachste Aufstieg“ bedeutet. Aus dieser Interpretation wird somit das geographische Datum:

35° 53' 0'' N; 76° 31' 0'' O; Lambha Pahar; K2; >8000 m ü. MSL; schwerster Normalweg 8000+


## Merkmale geographischer Daten

Anhand der bereits eingeführten Beispiele von Geodaten (Temperatur am Havann Airport, Lambha Pahar Normalweg) wird deutlich, dass die Attribute von Raumobjekten nahezu beliebige Ausprägungen aufweisen können. Manche dieser Ausprägungen können physikalischer Natur sein oder beschreiben soziologische Aspekte, verweisen auf Eigentumsrechte, sind fortlaufende Nummern etc.. Sie können Orte identifizieren (z.B. Adressen) oder Räume (z.b. manche Postleitzahlen). Sie können Maßzahlen sein (z.B. Einwohner/Fläche) oder kategoriale Ausprägungen haben (beliebte Kneipe, unbeliebte Kneipe). Da es in den Wissenschaften üblich ist mit Werten, Attributen und ihren Ausprägungen zu arbeiten, sind diese auch im Bereich Geographischer Informationssysteme bekannt. Die Skalenniveaus sind bereits aus der Statistik bekannt und werden Nominal-, Ordinal- und Kardinalskala genannt. Sind Merkmalsausprägungen zeitabhängig werden sie als zyklisch bezeichnet.

So einfach Geodaten erzeugt werden können, begegnen wir einer bekannten Problematik. Es ist zwar eindrucksvoll die Temperatur am Flughafen von Havanna um 8.00 Uhr lokaler Zeit am 17.09.2009 als Repräsentation des Wetters verfügbar zu haben. Doch wie gut beschreibt diese Repräsentation des Wetters den Durchzug eines Hurrikans um 8.15 Uhr des gleichen Tages?

Geodaten sind Merkmalsausprägungen, die hinsichtlich eines spezifischen Zwecks, Geoobjekten (diskrete Gegenstände oder kontinuierliche Raumeigenschaften) zielführend charakterisieren. Geoobjekte sind immer Repräsentationen real existierender Objekte, die durch eine Position im Raum direkt (z.B. durch Koordinaten = Geometrie) oder indirekt (z.B. durch Beziehungen = Topologie) referenzierbar (=verortet) sind. Sie sind immer formale Kodierungen der Eigenschaften und der zugehörigen Interpretation (=Informationen) dieser echten Objekte (vgl. Abb. 01-08).
{: .notice--info}

<html>
 <a  href="https://www.flickr.com/photos/environmentalinformatics-marburg/13898323961" title="01-08-Geoobjekt-schema1 by Environmental Informatics Marburg, on Flickr"><img src="https://farm8.staticflickr.com/7419/13898323961_21d8beca23_n.jpg" width="50%"  alt="01-08-Geoobjekt-schema1"></a>
</html>

*Abbildung 01-08: Schematische Strukturierung eines Geoobjekts in räumliche, dynamische und inhaltliche Aspekte (GIS.MA 2009)*


#### Kartenprojektionen in GI-Systemen

Die geographischen Winkel Länge und Breite referenzieren jeden Punkt auf der Oberfläche der Erde mit hoher skalierbarer Genauigkeit. Sie beziehen sich auf die wohldefinierte, dreidimensionale idealisierte Oberfläche der Erde. Diese Körpergestalt der Erde nutzt bekannte und durch Konvention festgelegte Referenzpunkte: das Königliche Observatorium von Greenwich für den Bezugsmeridian, das Schwerkraftzentrum der Erde und die Halbachsen des Referenzellipsoids der Erde als Annäherung an ihre wahre Gestalt.

Mit Hilfe dieser Parameter sind ausreichend genaue Lokalisationen aller Geoobjekte möglich. Gleiches gilt für die Analyse und Berechnung ihrer geometrischen Beziehungen. Historisch gesehen sind diese Aufgaben nicht auf einem Sphäroid durchgeführt worden sondern auf zweidimensionalen Karten die als projiziertes Abbild der Erde verwendet wurden. Auch heute besteht für sehr viele Anwendungen und Daten die Notwendigkeit eine verebnete zweidimensionale Projektionen der Erdoberfläche zu nutzen. So sind:

  * alle Ein- und Ausgabekarten zweidimensional
  * alle Rasterdatensätze (Satellitendaten, Luftbilder) zweidimensional, da quadratische Netze sich nicht verzerrungsfrei und ohne Überschneidungen oder Lücken auf eine Kugel aufbringen lassen


Eine Kartenprojektion ist nun eine mathematische Methode mit der man die gekrümmte Oberfläche der dreidimensionalen Erde auf die flache, zweidimensionale Karte überträgt. Dies erfolgt in zwei Schritten:

  - Auswahl eines geeigneten Referenzmodells für die Kugelgestalt der Erde
  - Transformation der geographischen Koordinaten (Länge und Breite) in ein kartesisches Koordinatensystem (x und y oder Rechtswert und Hochwert)


Im euklidischen Raum wird durch Bestimmung der x,y Koordinate ein Punkt in der Ebene (zweidimensional) verortet. Obwohl der dreidimensionale euklidische Raum auch die aus geographischem Winkel bestimmten Positionen abbilden kann, ist aus den oben genannten Gründen die Projektion von sphärischen Koordinaten in ein zweidimensionales kartesisches Bezugssystem üblich und meistens sinnvoll.

Kartenprojektionen können also als Transformation der von sphärischen Koordinaten der geographische Länge und Breite in kartesische Koordinaten y,x (Hochwert, Rechtswert) verstanden werden.


Da es sich bei allen Transformationen um sphärische Trigonometrie handelt und Geo-Datensätze beliebig unterschiedliche Referenzellipsoide und/oder geodätische Systeme als Grundlage haben (können), ist es von essentieller Bedeutung für das Arbeiten mit GI-Systemen diese Parameter und ihre Merkmale zu kennen und interpretieren zu können.




#### Das geodätische Datum

Bei einer kleinräumigen Betrachtungsweise ist die Genauigkeit einer auf ein Referenzellipsoid bezogenen Koordinatenbestimmung völlig ausreichend. Spannend ist, dass erst mit der Entwicklung von interkontinentalen Raketen in der ersten Hälfte des 20. Jhds. eine neue Dimension der Genauigkeit für die praktische Anwendung angestrebt wurde. In der Anwendung ist nämlich eine senkrechte Projektion auf das Ellipsoid unmöglich. Die senkrechte Projektion auf das auf Meeresniveau angenäherte Ellipsoid weicht um die sogenannte Lotabweichung von der wirklichen Senkrechten, wie sie durch ein gravitatives Schnurlot dargestellt wird, ab. Bei Vermessungen, die genauer sein sollen als etwa 0,5 Meter/1000 Meter (z.B. zur Berechnung der Ballistik von Interkontinentalraketen oder der Kontinentaldrift…), muss dieser Effekt berücksichtigt werden und die Messungen korrigieren zu können (Abb. 03-10).


<html><a href="https://www.flickr.com/photos/environmentalinformatics-marburg/14004801373" title="03-10 by Environmental Informatics Marburg, on Flickr"><img src="https://farm3.staticflickr.com/2919/14004801373_57decb7d14_o.png" width="529" height="278" alt="03-10"></a></html>

**Abb. 03-10: Differenz zwischen wahrer Lotrichtung und Ellipsoidnormale (=Lotabweichung) der zugehörigen Bezugskörper des Ellipsoids und Geoids (GIS.MA 2009)**

Das Referenzmodell für die sich räumlich (und auch zeitlich) unterschiedlich ausprägende Schwere der Erde ist ein sogenanntes Geoid. Die Abbildung zum Erdschwerefeld visualisiert stark überhöht und farblich hervorgehoben diese Schwereanomalien.

*defekte Abbildung*

<!--
{{  http://upload.wikimedia.org/wikipedia/commons/5/56/Geoids_sm.jpg  }}

//Abb. 03-11: Stark überhöhte Visualisierung des Erdschwerefelds (Geoid) (NASA 2005)//
-->

Für genaue Messungen oder möglichst exakte Kartenprojektionen müssen beide Bezugskörper, das Ellipsoid und das Geoid, berücksichtigt werden. Die Abbildung zur Schwerevariation und zu einer weiteren Alternative zeigen die konzeptuellen Probleme bei der Berücksichtigung des Geoids und des Referenzellipsoids für eine exakte Berechnung von Koordinaten. In der klassischen Vermessungstechnik wird hierzu, möglichst im Zentrum des abzubildenden Erdausschnittes, ein Referenzpunkt gesetzt (Fundamentalpunkt), der zusammen mit dem Referenzellipsoid das sogenannte geodätische Datum ergibt.

<html><a href="http://upload.wikimedia.org/wikipedia/commons/4/41/Geoundaequrp.png" title="03-10 by Environmental Informatics Marburg, on Flickr"><img src="http://upload.wikimedia.org/wikipedia/commons/4/41/Geoundaequrp.png" width="529" height="278" alt="03-10"></a></html>

**Abb. 03-12: Veranschaulichung der Schwerevariation entlang des Äquators bezogen auf eine kreisförmige Referenzfläche (schwarz) (Dandor 2006)**


<html><a href="http://upload.wikimedia.org/wikipedia/commons/7/78/Geoundnsrp.png" title="03-10 by Environmental Informatics Marburg, on Flickr"><img src="http://upload.wikimedia.org/wikipedia/commons/7/78/Geoundnsrp.png" width="529" height="278" alt="03-10"></a></html>

**Abb. 03-13: Birnenform als Näherung der Erdfigur im Vergleich zum elliptischen Querschnitt (schwarze Linie) (Dandor 2006)**


##### Das geodätische System

Seit der Satellitenvermessung mit globalen Positionierungssystemen (GPS) sind viele, unabhängige Messungen bezogen auf die reale Erdgestalt verfügbar, so dass nicht länger vom geodätischen Datum gesprochen wird sondern vom geodätischen System

Das World Geodetic System 1984 (WGS 84) ist derzeit das am meisten verwendete geodätische Referenzsystem und dient als einheitliche Grundlage für Positionsangaben auf der Erde und im erdnahen Weltraum. Geodätische Systeme sind, anders als das geodätische Datum, global konstruiert und bestehen aus dem Referenzellipsoid, dem eingemessenen Geoid, und zwölf Fundamentalstationen, über die der Bezug zur Erdkruste über zeitabhängige Koordinaten bestimmt wird.

Betrachten Sie die Abbildung zu den Referenzellipsoiden. Sie zeigt schematisch (zweidimensional) die Verschiebungen von Referenzellipsoiden bezogen auf das Geoid, also die wahre Erdoberfläche. Die Sterne markieren den Mittelpunkt des jeweiligen Körpers. Versuchen Sie sich zu verdeutlichen welche Parameter notwendig sind um diese Verschiebung durchzuführen.

*defekte Abbildung*

<!--
<html>
<a href="https://www.flickr.com/photos/environmentalinformatics-marburg/14004801273" title="03-14 by Environmental Informatics Marburg, on Flickr"><img src="https://farm3.staticflickr.com/2907/14004801273_84e8d2ce84_m.jpg" width="240" height="190" alt="03-14"></a>
</html>

**Abb. 03-14: Verschiebungen von Referenzellipsoiden bezogen auf das Geoid/wahre Erdoberfläche (GIS.MA 2009)**
