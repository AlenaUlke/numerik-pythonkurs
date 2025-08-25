(installationsempfehlungen)=
# Installationsguide

Python wird in einer Vielzahl von Bereichen eingesetzt, darunter Webentwicklung, Datenanalyse, maschinelles Lernen, wissenschaftliches Rechnen und sogar im Bereich der künstlichen Intelligenz. Die Vielseitigkeit der Sprache, zusammen mit ihrer großen Gemeinschaft und der riesigen Sammlung von Bibliotheken und Tools, macht Python zu einer hervorragenden Wahl für verschiedenste Anwendungen. Ein Grund für Pythons weitreichenden Einsatzmöglichkeiten sind die umfangreichen [Standardbibliothek](https://docs.python.org/3/library/), welche größtenteils plattformunabhängig verwendbar sind und für zahlreiche Anwendungsfälle bereits die passenden Lösungen bieten.


Damit wir in der ersten Kurseinheit direkt starten können, bitten wir Sie, im Vorfeld die benötigte Entwicklungsumgebung zu installieren. Wir werden die Anaconda Distribution verwenden. Anaconda ist eine Python-Distribution, was bedeutet, dass es neben Python auch eine Vielzahl nützlicher Bibliotheken und Werkzeuge, wie **Jupyter Notebook** und ein eigenes System für virtuelle Umgebungen, mitbringt – all das, was wir in diesem Kurs verwenden möchten.

Anaconda bietet eine All-in-One-Lösung, die sowohl Python als auch wichtige Bibliotheken und Werkzeuge umfasst. Das **Jupyter Notebook** ist für diesen Kurs besonders praktisch, da es uns ermöglicht, in einer einzigen Datei sowohl Programmcode als auch Texte, Formeln und Bilder zu integrieren. So können wir beispielsweise die Aufgabenstellung direkt über dem Code platzieren und mit erläuterndem Text versehen. Dies schafft eine übersichtliche und interaktive Arbeitsumgebung, die das Lernen und die Bearbeitung der Übungen erleichtert.

Für die Installation von Anaconda gehen Sie bitte wie folgt vor:

## Schritt 1 - Anaconda herunterladen
Laden Sie Anaconda [hier](https://www.anaconda.com/download/success) herunter. 
Sie werden zu einer Seite weitergeleitet, auf der Sie zunächst ihr Betriebssystem auswählen müssen, um dann die entsprechende Datei herunterzuladen. Für jedes Betriebssystem haben wir die richtige Wahl rot umrandet.

Falls Sie MacOS verwenden, hängt die richtige Wahl von dem Prozessors Ihres Mac-Computers ab. Wenn ein Apple M1, M2, M3, M4 Prozessor oder neuer verbaut worden ist, wählen Sie die Variante *Apple silicon*.

::::{tab-set} 

:::{tab-item} Windows
```{figure} img/anaconda/anaconda_install_windows.jpg
   :figclass: center
   :width: 100%
```
:::

:::{tab-item} MacOS
```{figure} img/anaconda/anaconda_install_mac.jpg
   :figclass: center
   :width: 100%
```
:::

:::{tab-item} Linux
```{figure} img/anaconda/anaconda_install_linux.jpg
   :figclass: center
   :width: 100%
```
:::
::::

Nun haben Sie die aktuelle Version von Python (Python 3.13) heruntergeladen.

## Schritt 2 - Anaconda installieren
Starten Sie den heruntergeladenen Installer. Klicken Sie so lange **Next >** und **I Agree** bis Sie den Dateipfad wählen
müssen. Unter Windoes wählt Anaconda zum Beispiel den Pfad `C:\Users\Username\anaconda3` als Standard. 
```{figure} img/anaconda/anaconda_installation_4.png
```
Wir empfehlen diesen Standardpfad nicht zu ändern. Falls Sie dies dennoch tun möchten, achten Sie darauf, dass am Ende des Dateipfades `[…]\anaconda3` bzw.  `[…]\anaconda` steht. Ansonsten wird das übergeordnete Verzeichnis, in unserem Beispiel `Username`, mit diversen Dateien zugemüllt.


Abschließend müssen Sie Einstellungen auswählen, bevor Sie den Download durchführen. Wir empfehlen die Standardeinstellungen nicht zu ändern. Ihre Auswahl sollte wie folgt aussehen:
```{figure} img/anaconda/anaconda_installation_5.png
```
Nun können Sie **Install** drücken. Anaconda wird nun installiert.

## Schritt 3 - Anaconda starten
Zum Abschluss möchten wir noch sicherstellen, dass der Download tatsächlich einwandfrei verlaufen ist. Starten Sie dazu den Anaconda Navigator. Sie finden ihn, wenn Sie in ihrem Computer/Laptop nach Anaconda suchen.
```{figure} img/anaconda/anaconda_installation_6.png
```

\
Hier starten Sie das bereits mitinstallierten Jupyter Notebook:
```{figure} img/anaconda/anaconda_installation_7.png
```
Jupyter Notebook funktioniert für die Standardbrowser Google Chrome, Mozilla Firefox und Microsoft Edge sehr gut. In dem entsprechenden Browser öffnet sich ein Fenster das wie folgt aussehen sollte:
```{figure} img/anaconda/anaconda_installation_8.png
```
Wenn Sie hier angekommen sind, ist der Download erfolgreich gewesen. Genaueres zur Funktionsweise von **Jupyter Notebooks** finden Sie im [kommenden Kapitel](./funktionsweise_jupyter_notebook.md). Falls Sie Probleme beim Download haben, nutzen Sie Ihre bevorzugte Suchmaschine (oder ChatGPT). Ansonsten versuchen wir die Probleme gemeinsam in der ersten Kurseinheit zu lösen. 




