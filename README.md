# Hyperloop

Hyperloop-Projektarbeit an der Hochschule Emden/Leer

## Installiere MATLAB und das IO-Blockset von Speedgoat.

### Linux

#### Installation von Matlab
Lade [Matlab](https://de.mathworks.com/downloads/) herunter. Erstelle ein Verzeichnis an einen beliebigen Ort und Entpacke die Datei und führe die folgenden Befehle aus.

```bash
xhost +SI:localuser:root 
sudo -H ./install 
xhost -SI:localuser:root
```

#### Installation des IO-Blocksets von Speedgoat


Nach der Installation von MATLAB muss das IO-Blockset von Speedgoat installiert werden. Dafür ist es erforderlich, einen Account bei Speedgoat zu erstellen, um Zugriff auf die [Blockset-Dateien](https://www.speedgoat.com/extranet#/Downloads) zu erhalten.

Lade die ZIP-Datei herunter und entpacke sie in dasselbe Verzeichnis, in dem MATLAB installiert wurde.

Anschließend muss in MATLAB über den internen Dokumentennavigator das Installationsverzeichnis geöffnet werden. Um das IO-Blockset zu installieren, führe in der MATLAB-Konsole den folgenden Befehl aus:


```bash
speedgoat_setup
```