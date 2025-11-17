# "Entwicklung von LLM-basierten Ansätzen zur Automatisierung und Auswertung von Geschäftsprozessen"

In diesem Repository finden Sie den Code aus der Veranstaltung und die referenzierten Notebooks.

# Setup-Anleitung

## Code herunterladen

-   In GitHub auf "<> Code" klicken und "Download ZIP" auswählen.
-   Den Zip-Ordner im User-Verzeichnis extrahieren.
-   Eine Kommandozeile starten (Windows-Taste + "cmd" eingeben bzw. bei Mac "Terminal" starten).
-   Mittels cd (change directory) zu dem extrahierten Ordner bewegen (üblicherweise "cd thl-main").

## Python Voraussetzungen prüfen

-   Eine **Python-Installation** ist vorhanden.\
    Version prüfen mit:

    ``` bash
    python --version
    ```

    oder (abhängig vom System):

    ``` bash
    python3 --version
    ```

-   Sollte kein Python 3 installiert sein, bitte auf python.org die aktuellste Python-Umgebung herunterladen und installieren.

## Virtuelle Umgebung erstellen

### 1. venv anlegen

``` bash
python -m venv venv
```

Dadurch wird ein Ordner `venv/` erzeugt, der die Python-Laufzeitumgebung für
diese Veranstaltung enthält.

### 2. venv aktivieren

**Windows:**

``` bash
venv\Scripts\activate
```

**macOS / Linux:**

``` bash
source venv/bin/activate
```

Nach der Aktivierung sollte ein `(venv)` vor der Kommandozeile
erscheinen.



## Installation der Abhängigkeiten

Mit aktiver virtueller Umgebung:

``` bash
pip install -r requirements.txt
```

## VSCode installieren

-   Bitte laden Sie unter https://code.visualstudio.com/download Visual Studio Code herunter und installieren Sie es.


# Notebooks ausführen

Sie sollten nun mit einem Doppelklick auf die Notebook-Dateien (.ipynb-Endung) die jeweiligen Notebooks starten können (in VSCode). Bitte wählen Sie den richtigen Interpreter in VSCode aus ("Select Kernel" -> Python Environments und dann die erzeugte virtual environment auswählen, d.h. den Pfad zur python.exe im Scripts-Ordner selektieren).