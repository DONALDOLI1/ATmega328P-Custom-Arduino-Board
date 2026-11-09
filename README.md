# ATmega328P Custom Development Board

<div align="center">

**Custom ATmega328P development board designed with KiCad 9.0.7**

*Arduino IDE · FTDI / USB-to-serial · Embedded electronics*

</div>

---

## Français

### Présentation

Ce projet présente une carte de développement personnalisée basée sur le microcontrôleur **ATmega328P**. La carte a été conçue sous **KiCad 9.0.7**, puis fabriquée, assemblée et testée.

Elle met à disposition les principales broches d'entrée/sortie du microcontrôleur ainsi que des connecteurs dédiés à l'alimentation et à la programmation.

### Programmation

Le microcontrôleur est programmé à l'aide de l'**IDE Arduino**. Le téléversement du programme s'effectue à travers un **adaptateur FTDI USB-série**, en utilisant une liaison série UART.

Le tutoriel [Passion Électronique – Programmer un ATmega328P](https://passionelectronique.fr/programmer-atmega328p/) a servi de ressource pour comprendre cette méthode de programmation.

> La présence et la configuration d'un bootloader ne sont pas documentées ici ; elles pourront être précisées ultérieurement.

### Caractéristiques principales

- Microcontrôleur : ATmega328P (référence de la nomenclature : ATmega328P-P).
- Conception électronique et PCB : KiCad 9.0.7.
- Alimentation d'entrée indiquée sur le schéma : 8 à 20 V DC.
- Régulation : L7805 pour le 5 V et LM1117T pour le 3,3 V.
- Horloge externe : quartz 16 MHz avec deux condensateurs de 22 pF.
- Programmation : Arduino IDE via adaptateur FTDI USB-série.
- Connecteurs accessibles pour les entrées/sorties numériques et analogiques.
- LED rouge et LED verte intégrées.

### Documents du projet

Les fichiers techniques sont disponibles dans le dossier [`documents/`](documents/) :

| Document | Accès |
|---|---|
| Schéma électronique | [SCHEMATIC ATMEGA328P.pdf](documents/SCHEMATIC%20ATMEGA328P.pdf) |
| Implantation des composants | [COTE COMPOSANT ATMEGA 328P.pdf](documents/COTE%20COMPOSANT%20ATMEGA%20328P.pdf) |
| Typon du circuit imprimé | [TYPON ATMEGA328P.pdf](documents/TYPON%20ATMEGA328P.pdf) |
| Liste des composants | [liste_composants.pdf](documents/liste_composants.pdf) |

Les photographies de la carte et les vues de réalisation sont regroupées dans [`images/`](images/).

### Galerie

Quelques vues du projet :

<p align="center">
  <img src="images/IMG-20260506-WA0021-1.jpeg" alt="Carte ATmega328P - vue 1" width="32%">
  <img src="images/IMG-20260507-WA0021-1.jpeg" alt="Carte ATmega328P - vue 2" width="32%">
  <img src="images/IMG-20260509-WA0026-1.jpeg" alt="Carte ATmega328P - vue 3" width="32%">
</p>

<p align="center">
  <img src="images/IMG-20260509-WA0033-1.jpeg" alt="Carte ATmega328P - vue 4" width="32%">
  <img src="images/IMG-20260508-WA0001-1.jpeg" alt="Carte ATmega328P - vue 5" width="32%">
  <img src="images/IMG-20260506-WA0025.jpg" alt="Carte ATmega328P - vue 6" width="32%">
</p>

### État de réalisation

- [x] Conception électronique et PCB
- [x] Fabrication de la carte
- [x] Assemblage des composants
- [x] Essais de la carte
- [x] Programmation avec Arduino IDE et téléversement via FTDI

*Les mesures détaillées et les résultats chiffrés des essais ne sont pas présentés dans cette version.*

---

## English

### Overview

This project presents a custom development board based on the **ATmega328P** microcontroller. The board was designed using **KiCad 9.0.7**, then manufactured, assembled and tested.

It provides access to the microcontroller's main digital and analog I/O pins, together with dedicated power and programming connectors.

### Programming

The microcontroller is programmed using the **Arduino IDE**. Firmware is uploaded through an **FTDI USB-to-serial adapter** over a UART serial connection.

The [Passion Électronique – Programming an ATmega328P](https://passionelectronique.fr/programmer-atmega328p/) tutorial was used as a learning resource for this programming method.

> The presence and configuration of a bootloader are not documented here and can be specified later.

### Main features

- Microcontroller: ATmega328P (the bill of materials specifies ATmega328P-P).
- Electronic and PCB design: KiCad 9.0.7.
- Input supply indicated on the schematic: 8–20 V DC.
- Voltage regulation: L7805 for 5 V and LM1117T for 3.3 V.
- External clock: 16 MHz crystal with two 22 pF capacitors.
- Programming: Arduino IDE via FTDI USB-to-serial adapter.
- Accessible digital and analog I/O connectors.
- Integrated red and green LEDs.

### Project documentation

The technical files are available in the [`documents/`](documents/) folder:

| Document | Access |
|---|---|
| Electronic schematic | [SCHEMATIC ATMEGA328P.pdf](documents/SCHEMATIC%20ATMEGA328P.pdf) |
| Component placement | [COTE COMPOSANT ATMEGA 328P.pdf](documents/COTE%20COMPOSANT%20ATMEGA%20328P.pdf) |
| PCB copper artwork | [TYPON ATMEGA328P.pdf](documents/TYPON%20ATMEGA328P.pdf) |
| Bill of materials | [liste_composants.pdf](documents/liste_composants.pdf) |

Project photographs and board views are collected in the [`images/`](images/) folder.

### Gallery

A selection of project views:

<p align="center">
  <img src="images/IMG-20260506-WA0021-1.jpeg" alt="ATmega328P board - view 1" width="32%">
  <img src="images/IMG-20260507-WA0021-1.jpeg" alt="ATmega328P board - view 2" width="32%">
  <img src="images/IMG-20260509-WA0026-1.jpeg" alt="ATmega328P board - view 3" width="32%">
</p>

<p align="center">
  <img src="images/IMG-20260509-WA0033-1.jpeg" alt="ATmega328P board - view 4" width="32%">
  <img src="images/IMG-20260508-WA0001-1.jpeg" alt="ATmega328P board - view 5" width="32%">
  <img src="images/IMG-20260506-WA0025.jpg" alt="ATmega328P board - view 6" width="32%">
</p>

### Project status

- [x] Electronic and PCB design
- [x] Board manufacturing
- [x] Component assembly
- [x] Board testing
- [x] Arduino IDE programming and FTDI uploading

*Detailed measurements and numerical test results are not included in this version.*

---

<div align="center">

**Project designed and developed by OLI OLI DONALD**  
Electrical Engineering and Intelligent Systems · Cameroon

</div>
