# Image Classifier zur automatisierten Müllklassifizierung und Trennhilfe

## Introduction

Willkommen zum Projekt Image Classifier zur automatisierten Müllklassifizierung und Trennhilfe.  
Ziel dieses Projekts ist die Entwicklung eines Bildklassifikationsmodells zur automatischen Erkennung von Abfallkategorien an der Hochschule der Medien.  
Das Modell unterscheidet zwischen Pfandflaschen, Papier, Plastik, Restmüll sowie Fremdmüll / kein Müll.

Der Fokus liegt auf einer praxisnahen Klassifikation, die sich an den real vorhandenen Entsorgungsmöglichkeiten der Hochschule orientiert.  
Das Projekt umfasst die Datensammlung, Datenaufbereitung, Modellierung, Training sowie die Auswertung der Ergebnisse.


## Installation und Ausführung

### 1. Repository klonen

Kopiere das Projekt in ein lokales Verzeichnis deiner Wahl.

```
git clone https://github.com/byGamsa/slt-ai.git
```

### 2. Voraussetzungen

Für die Ausführung wird eine funktionierende Git LFS Umgebung benötigt, da die verwendeten Modelldateien sehr groß sind.
Stelle sicher, dass Git LFS auf deinem System installiert und korrekt konfiguriert ist.
Ohne Git LFS wären die Dateien zu groß für ein normales Git Repository und könnten nicht korrekt versioniert oder geklont werden.

```
git lfs install
```

### 3. Umgebung einrichten

Für die lokale Ausführung wird empfohlen eine Conda Umgebung zu verwenden.  
Die benötigten Abhängigkeiten können über das Notebook automatisch installiert werden oder manuell über die bereitgestellte Installationszelle.

### 4. Notebook starten

Öffne das Hauptnotebook im gewünschten Entwicklungsumfeld, zum Beispiel Jupyter Notebook, Jupyter Lab oder Visual Studio Code.

Um Jupyter Lab zu starten, kann folgender Befehl in deiner Entwicklungsumgebung, zum Beispiel im Terminal von Visual Studio Code, eingegeben werden:

```
jupyter lab
```

### 5 Ausführen

Führe alle Zellen des Notebooks nacheinander aus.  
Dabei werden die Daten geladen, vorverarbeitet, die Modelle trainiert und die Ergebnisse ausgewertet.


## Projektinformationen

Dieses Projekt ist Teil der Prüfungsleistung im Modul 113451 Ausgewählte Anwendungen der KI im Studiengang Medieninformatik an der Hochschule der Medien Stuttgart.


## Autoren

Julia Ebert (je073) <br>
Lars Gerigk (lg107) <br>
Joel Starkov (js486) <br>

<b>Professor:</b> Prof. Dr. Johannes Maucher


## Lizenz

Dieses Projekt dient ausschließlich zu Lehr und Lernzwecken.
