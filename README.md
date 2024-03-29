Ma config Home Assistant
=============================================================

![Screenshot](https://raw.githubusercontent.com/hokagegano/HA2019/master/HA.png)

![Screenshot](https://raw.githubusercontent.com/hokagegano/HA2019/master/HA2.png)

![Screenshot](https://raw.githubusercontent.com/hokagegano/HA2019/master/HA3.png)
![Screenshot](https://raw.githubusercontent.com/hokagegano/HA2019/master/HA4.png)
![Screenshot](https://raw.githubusercontent.com/hokagegano/HA2019/master/HA5.png)
![Screenshot](https://raw.githubusercontent.com/hokagegano/HA2019/master/HA6.png)
![Screenshot](https://raw.githubusercontent.com/hokagegano/HA2019/master/HA7.png)
![Screenshot](https://raw.githubusercontent.com/hokagegano/HA2019/master/HA8.png)

Les composants de la configuration :
- Media player : SqueezeBox, Télé Panasonic, Nvidia Shield ChromeCast, Nvidia Shield Plex, MPD
- Lights : Hue
- Google Calendar
- Camera : PS3Eye, Kinect et Webcam Nexus 7
- Presence Detection : Nut, Xiaomi MiBand2, Happy Bubbles
- RFXCom433E
- Devices 433mhz : 3 sondes Température/Humidité, 2 détecteurs de mouvement
- Devices ZigBee : Hue motion detector (mouvement, temperature, humidité)
- Mise en place de Telegram
- Google HOME
- Xiaomi Vacuum cleaner 2
- Imprimantes 3D via Octoprint pour la Creality CR10 et MQTT Octoprint pour l'Anet A8

Automations:
- Le reveil matin avec allumage des lumières progressif
- L'annonce du matin (rdv, conditions de surf, meteo, traffic sur la route)
- Extinction des lumières apres que la derniere personne quitte le logement
- Allumage des lumières quand le soleil se couche.
- Allumage des lumières une fois le soleil couché si quelqu'un rentre tard.
- Envoi des videos sur l'intrusion domicile (alarme)
- Allumage automatique des wc
- Allumage automatique de la salle de bain
- Allumage automatique de la chambre quand je monte à l'etage et que la télé est eteinte (à partir d'une certaine heure).
- Changement de couleur de toutes le lampes de couleurs HUE de manière synchronisée (mode soirée) toutes les minutes.
- Si le calendrier a un evenement RTT, la lumière ne s'allume pas le matin.
- La modification de l'heure du réveil Android a pour incidence la mise à jour du reveil sous Home Assistant (via Tasker).
- Mise en place d'un mode conversationnel avec telegram : envoi des conditions de surf en temps réel, et obtention des temperatures.
- Extinction automatique des imprimantes 3D apres impression (avec une temporisatiopn de 5 minutes pour baisser la temperature de la buse et du plateau).
- Positionnement automatique du flag d'extinction des imprimantes 3D quand je vais me coucher (si j'avais oublié de les activer)
# HA2019
