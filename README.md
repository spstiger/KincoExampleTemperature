[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# KincoExampleTemperature
An example project for displaying a temperature value in a Kinco HMI.

![Temperaturanzeige](/spstiger_Beispiel_Temperaturanzeige.png)

Dieses Beispielprogramm für ein Kinco GT070HE zeigt, wie man leicht eine Temperaturanzeige auf dem HMI darstellen kann. Es beinhaltet folgende Funktionen und Anpassungen:

* Zahlenanzeige für Temperatur mit Nachkommastellen und Einheit als Label (°C)
* Rechtsbündige Ausrichtung des Werts für bessere Darstellung
* Anpassung aller Schriftarten auf Arial Nova für attraktive Darstellung
* Abgerundetes Rechteck, Überschrift für Messwert und Icon als statisches Bitmap (importiertes PNG)
* Simulation eines unskalierten Rohwertes als PT100-Messwert (wie im Temperaturmodul für KS-SPS)
* Eigene Button (selbst erstellte VG-Vektorgrafik) für Buttons für Wertänderung (Hoch / Runter) mit Jog-Funktion (Multizustandschalter) 
* Anpassung der Nummerntastatur mit passender Farbdarstellung und Arial Nova als Tastaturschriftart
* Anpassung der Systemmeldung für falsche Eingabe des Rohwertes - Sprache und Schriftart der Meldung

Das Projekt wurde für das Kinco HMI GT070HE mit einer Auflösung von 1.024 x 600 Pixeln erstellt. Die Kinco HMI der GL100E und GT100E-Serie sowie das GT070E2 haben eine gleiche Auflösung. Das Projekt kann für diese Modelle einfach per Rechtsklick auf das HMI in DTools konvertiert werden. 
Für HMI mit anderer Auflösung ist eine Konvertierung über diesen Weg ebenfalls möglich, es werden aber wahrscheinlich Nacharbeiten notwendig, um die Darstellung an das HMI anzupassen.

Das Programm wurde in der Entwicklungssoftware Kinco DTools 3.5.3 erstellt.
