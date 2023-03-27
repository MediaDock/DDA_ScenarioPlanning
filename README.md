Switchdrive Video Dummies: 
https://drive.switch.ch/index.php/s/AtrdYISgIGqtdnm

Metashape Scan anleitung: 
https://sites.hslu.ch/werkstatt/3d-scan-photogrammetrie/

## C4D Projection Mapping herstellen
### Raumplanung
Bilder an Referenzbildern ausrichten und die richtigen Dimensionen für das Objekt nutzen. 

Maxon Training Tool: 
Using a Reference Picture
https://www.youtube.com/watch?v=ghBwlgMImKc

- Raumskizze anfertigen
- Floorplan als Hintergrund einfügen
	-  Ansicht "von oben" wählen 
	-  Menu > Ansicht > Ansichts-Voreinstellung > öffnet ein Attribute Fenster 
	- Darin Tab Hintergrund anwählen und unter Bild den Florplan hineinladen

- Viereck in den Raummassen zeichnen 
	-  Background Bild an der richtigen Raumgrösse anpassen. 
	- Viereck extrudieren bis Raumhöhe erreicht ist
	- Quader in bearbeitbares Objekt umwandeln 
	- Decke löschen (damit du mit der Kamera besser in den Raum hinein kommst)


### Image Projection
Cinema 4D Kamera zum "Projektor" umbauen:

Nicko16:
Image Projection
https://www.youtube.com/watch?v=yCI8-XcaWrQ

- Kameras Platzieren: 2 Projektionen und einen Blick
- Projektionsobjekt platzieren (Holzrugel / Holzkeil) 
	- evt. Texturen erneut verknüpfen diese findest du im Ordner (

- Eröffne ein neues Material im Material Browser
	- öffne den Material Editor des neuen Materials
	- deaktiviere alle attribute color ect. ausser luminance und Alpha (Leuchten)
	- clicke unter Leuchten auf die drei Punkte (...) neben Textur
	- Füge ein Bild oder Video hinzu 
	- Füge die Textur zu einem Objekt hinzu (z.B. Raum oder Objekt)

- Textur animieren: 
	- öffne das Material im Material Editor
	- Leuchten Reiter > clicke aufs Bild > Animatin Reiter
	- hier kannst du die Animationspresets einstellen. 

- Textur halbtransparent machen: 
	- öffne das Material im Material Editor
	- Alpha Reiter 
	- Alpha Bild Deaktivieren (uncheck)
	- Textur Farbe 
	- Farbeinstellungen auf einen leichten Graubereich einstellen: z.B. #CECECE
	- je dunkler desto Transparenter wird die Projektion
		
- clicke auf das Material Tag des Objekts (z.B: Raum oder Objekt)
	- In den Material Tag Einstellungen nehmen wir nun die Mapping Einstellungen vor. 
	- clicke auf den Reiter "Tag"
	- clicke auf Projektion 
	- Wähle Kamera Mapping
	- Wähle mit der Pipette neben der nun wählbaren Kamera die Kamera aus in diesem ersten Bsp. Projektion Wand 
	- uncheck Kachel / Tile 
	- Jetzt sehen wir alles texturiert im Blickwinkel der Kamera
	- Um den Raum Wieder sichtbar zu machen müssen wir nun folgendes Machen:
	- wir brauchen ein zweites Material
	- Sichtbar machen des restlichen Raumes
	- Wir legen dieses auf den Rest des Raumes (Links neben dem VideoMaterial platzieren)

- Wiederhole die Prozedur für das zweite Objekt
		
		
### intermediate: Kamera kalibrieren und "Blickwinkel akkurat texturieren: 
Um die Szenerie "realisitscher" zu machen könnten wir den Raum noch mit einem Foto Texturieren: wie ein solches Kamera Mapping gemacht wird seht ihr hier. 
Auch, eine erste Möglichkeit wie solche realen Objekte mit virtuellen Objekten im Raum interagieren können werden wir sehen. 

Digital Meat: 
Projection Mapping
https://www.youtube.com/watch?v=C0976dRXG_A&t=2946s
