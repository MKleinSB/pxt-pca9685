# pxt-pca9685

Erweiterung für die PCA9685 16x Servodriver boards

| ![PCA9685 Board](https://github.com/MKleinSB/pxt-pca9685/blob/master/2.png "PCA9685 Board") | ![PCA9685 Board](https://github.com/MKleinSB/pxt-pca9685/blob/master/1.png "PCA9685 Board") |
| :----------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------: |
|                                            _PCA9685 Board 2€ von ebay_                                            |                                   _PCA9685 Board Grove Version von seeed_                                   |
|                                            _I2C Adress 0x40 (Standard)_                                            |                                   _I2C Adress 0x7F_                                   |

## Diese Erweiterung verwenden

Dieses Repository kann als **Erweiterung** in MakeCode hinzugefügt werden.

* öffne /
* klicke auf **Neues Projekt**
* Klicke auf **Erweiterungen** unter dem Zahnrad-Menü
* suche nach der URL dieses Repositories und importiere sie

## Blöcke
Bei der Standardadresse 0X40 ist keine Initialisierung notwendig

![Eine gerenderte Ansicht der Blöcke](https://github.com/MKleinSB/pxt-pca9685/blob/master/B2.png)


Bei der **Groveversion** mit der Adresse 0x7F muss beim Start die I2C-Adresse eingestellt werden.

![Eine gerenderte Ansicht der Blöcke](https://github.com/MKleinSB/pxt-pca9685/blob/master/B1.png)


## Unterstützte Boards

* for PXT/calliope
* for PXT/microbit

