# Voorbereidingen

In deze sectie lees je hoe je de benodigde software installeert om aan de slag te gaan met de Webots workshop.

## Installeren van Python

1. Ga naar de officiële Python-website: [https://www.python.org/](https://www.python.org/).
2. Download de nieuwste versie van Python voor jouw besturingssysteem.
3. Volg de installatiestappen op het scherm en zorg ervoor dat je de optie "Add Python to PATH" aanvinkt tijdens de installatie.   

## Installeren van Webots

1. Ga naar de officiele website: [https://cyberbotics.com/](https://cyberbotics.com/).
2. Download de versie voor jouw besturingssysteem.
3. Volg de installatiestappen op het scherm.

## Verkrijgen van de workshopbestanden

Om te starten heb je de workshopbestanden nodig met code, schema's en opdrachtinstructies.

:::::{card}
::::{tab-set}

:::{tab-item} Download ZIP
Download de bestanden als ZIP via:
[Download Workshop Bestanden](https://github.com/AvansMechatronica/simulatie_met_webots_workshop/archive/refs/heads/main.zip)

Pak het ZIP-bestand uit in een map die je makkelijk terugvindt.

:::

:::{tab-item} Git Clone

Als je al bekend bent met Git en github, kun je de bestanden ook via Github verkrijgen. Volg de onderstaande stappen:

* Maak een account aan bij [Github](https://github.com/) en login op dit account

* Open de [simulatie_met_webots_workshop](https://github.com/AvansMechatronica/simulatie_met_webots_workshop) repository

* Maak een Fork van de repository naar je eigen Github account door op het **Fork icoon**  te klikken:

![image](../images/fork.jpg)

* Volg de instructies, maar wijzig de naam van de nieuwe repository niet. Bevestig met **Create Fork**  

* Nu kun je de workshop clonen naar je lokale machine:

```bash
git clone https://github.com/<jouw_account_naam>/simulatie_met_webots_workshop.git
```

:::

::::

:::::

:::{warning}
Plaats de bestanden niet in een `OneDrive`-map. Dit kan compileerproblemen veroorzaken.
:::

## Installeren van benodigde Python-pakketten
Alvorens de workshopcode uit te voeren, moeten de benodigde Python-pakketten geïnstalleerd worden. Open een terminal of command prompt en navigeer naar de map met de workshopbestanden. Voer vervolgens het volgende commando uit:

```bash
cd <pad_naar_workshopbestanden>/workspace
pip install -r requirements.txt
```

## Testen van de installatie
Om de workshopcode te kunnen uitvoeren kun je een voorbeeld programma van Webots gebruiken. Start Webots en open een van de voorbeeldprojecten om te controleren of alles correct is geïnstalleerd. Doe dit door in Webots naar `File` > `Open Sample Project` te gaan en een van de beschikbare voorbeelden te selecteren. Een mooi voorbeeld is:

```
robots-->abb-->irb-->inverse_kinematics.wbt
```

Als dit voorbeeld correct werkt, betekent dit dat Webots en de benodigde Python-pakketten correct zijn geïnstalleerd. Je kunt natuurlijk ook andere voorbeeldprojecten openen om te controleren of alles naar behoren functioneert.