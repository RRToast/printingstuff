# Übung 1

#### Richard Reik & Tim Glass

### 1. a)

Zu häufig vorkommende und damit überflüssige Informationen.

### 1. b)

Name und Nummern zu häufig.  

- Schwesternnummer & -name je in Stationsdatei & Schwesterndatei
- Patientenname je in Patientendatei und Ärztedatei
- Medikamentennummer & -name je in Schwesterndatei & Meidkamentendatei

mögliche Probleme daraus:  

- irreführende "Verknüpfungen" bei diversen LookUp-Aktionen aus verschiedenen/mehreren Tabellen
- mehr Speicherplatz durch größere Datenmenge benötigt
- Suchoperationen dauern länger, da mehrere Tabellen untersucht/durchsucht werden müssen

### 1. c)

siehe Bild

testing super script  

ABC<sup>bla-super</sup>ABC  

testing sub script  

ABC<sub>bal-subber</sub>ABC

### 2. a)
```
π               ((((σ               (Waren)) ⋈               (Einzelbestellungen)) ⋈               (Bestellungen)) ⋈               (Kunden))
```
Ergebnis: Rosenheim & Ulm & UNBEKANNT(?)

### 2. b)
```
π               (σ               (BESTELLUNGEN) ⋈               (EINZELBESTELLUNGEN))
```
Ergebnis: S1

### 2. c)

```
π               (σ               (EINZELBESTELLUNGEN) ⋈               (WAREN))
```
Ergebnis: Schrauben & Nägel

### 2. d)

```
π               (σ               (KUNDEN) ⋈               (BESTELLUNGEN))
```
Ergebnis: O1 & O2

### 2. e)

```
π               (((σ               (KUNDEN) ⋈_Kundennr_ (BESTELLUNGEN)) ⋈               (EINZELBESTELLUNGEN)) ⋈               (WAREN))
```
Ergebnis: Muttern, Nägel & Schrauben

### 3.



### 4.

Das Data Dictionary wird auch "database about the database" genannt. Hierin werden alle Informationen über die logische Struktur der Datenbank gehalten.  
Die zwei verschiedenen Arten eines Data Dictionary sind ein "integrated data dictionary" (als Teil des DBMS) und ein "freestanding data dictionary"(third party/kommerzielle Software oder auch simple Datei).  
Beim integrated data dictionary ist als Pro zu nennen, dass es immer konsistent mit der eigentlichen Datenbank gehalten wird, da es vom DBMS selbst verwaltet wird.  
Als großer Vorteil der freestanding-Variante wird gesehen, dass diese es den Designern der DB erlaubt die DB unabhängig von der eigentlichen Implementierung zu designen. Ein Nachteil hiervon ist aber, dass spätere Änderungen der eigentlichen Implementierung möglicherweise nicht im Data Dictionary mit aufgenommen werden können und es somit keine korrekte Darstellung der DB mehr liefern kann.



