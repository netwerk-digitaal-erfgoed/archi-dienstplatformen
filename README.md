# ArchiMate uitwerking van het NDE architectuuronderzoek dienstplatformen

In dit project vind je de ArchiMate uitwerking van NDE architectuur uitwerking van het onderzoek naar dienstplatformen.

## Opzet

De architectuur van onderzochte dienstplatformen is uitgewerkt als extensie van de [Digitaal Erfgoed Referentie Architectuur (DERA)](https://dera.netwerkdigitaalerfgoed.nl/index.php/Hoofdpagina).

De modellen zijn gemaakt in de ArchiMate taal en zijn bedoeld om inzicht te geven in de architectuur van de dienstplatformen die onderzocht zijn in het NDE architectuuronderzoek.

Voor ieder dienstplatform is een aparte ArchiMate view gemaakt. Deze views zijn te vinden in de map `Views` in het ArchiMate project.

## Modellen bekijken

Om de ArchiMate modellen te bekijken kun je de [Archi](https://www.archimatetool.com/) tool downloaden en installeren.

1. Download [de laatste release](https://github.com/netwerk-digitaal-erfgoed/archi-dienstplatformen/releases).
2. Open de Archi tool.
3. Ga naar 'File' -> 'Import' -> 'Model From Open Exchange File...' en selecteer het gedownloade bestand.
4. Je kunt nu de verschillende modellen bekijken.


## Voor NDE medewerkers

Om mee te werken aan de ArchiMate modellen kun je de volgende stappen volgen:


Download [Archimate](https://www.archimatetool.com/download/):
Volg de instructies op de website om Archi te downloaden en te installeren.


Voor installatie op linux:

```
sudo apt-get install Archi-Linux64-5.3.0.tgz
```
checksum
```
sha1sum Archi-Linux64-5.3.0.tgz
```
extract
```
tar -xvzf Archi-Linux64-5.3.0.tgz
```

Voeg de plugin [coArchi – Model Collaboration for Archi](https://www.archimatetool.com/plugins/) toe aan Archi.

Zie [deze repo](https://github.com/archimatetool/archi-modelrepository-plugin/wiki).

Als je de plugin hebt geïnstalleerd kun je in Archi naar naar 'collaboration' -> '+ Import Remote Model to Workspace' om het model te importeren.
