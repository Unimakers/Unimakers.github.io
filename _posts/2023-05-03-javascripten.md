---
layout: post
title: La borne d'arcade
description: >
  Une borne d'arcade fais sous l'OS Recalbox et tout les outils du Makerspace 
tags: [Amiens]
author: author2
accent_color: '#E04750'
accent_image:
  background: '#2D2D36'
  overlay:    false
accent_image: /assets/img/project/Borne_d_arcade/salle-arcade-mikado.jpg

---

## Réalisation d'une borne d'arcade
> Réalisation d'une borne d'arcade dans les locaux d'Unilasalle Amiens encadré par Adrien Bracq (Enseignant Chercheur).

> **Petite Histoire:**
Les bornes d'arcade ont fait leur apparition dans les années 1930 avec l'arrivée des jeux électromécaniques tels que les flippers. Ceux-ci se sont rapidement popularisés, souvent de la taille d'un meuble et avec un coût relativement élevé. Peu de particuliers pouvaient se les offrir. C'est pour cette raison que des salles publiques ont vu le jour, où des dizaines de machines étaient disponibles. Les premières bornes d'arcade avec des jeux vidéo intégrés ont fait leur apparition dans les années 1960 en Amérique, avant de se populariser en Europe dans les années 1970 à 1980. Malheureusement, c'est à cette même période que les bornes d'arcade ont commencé à disparaître en Europe en raison de l'arrivée des consoles de jeux portables sur le marché.

### **Le but du projet:**

Le but de ce projet est de réaliser une borne d'arcade avec des anciens jeux d'arcades des années 1980.

### Réalisation du projet:

Les étapes pour construire une borne d'arcade sont les suivantes :

- Dessinez un design à la main pour déterminer les dimensions de la borne.

- Utilisez un logiciel de CAO, comme **[FreeCAD](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwj5odvWjeCBAxWMV6QEHQQbCjQQFnoECBUQAQ&url=https%3A%2F%2Fwww.freecad.org%2Findex.php%3Flang%3Dfr&usg=AOvVaw17WDYd8I-_k42_OpiwajPK&opi=89978449)**, **[Fusion360](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjQ4obojeCBAxUaVqQEHQGGBs4QFnoECBcQAQ&url=https%3A%2F%2Fwww.autodesk.fr%2Fproducts%2Ffusion-360%2Foverview&usg=AOvVaw0o3YgBfEPtwNNOSe69fjn3&opi=89978449)** ou **[SolidWorks](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwio86HxjeCBAxXTRUEAHeEFAGQQFnoECAgQAQ&url=https%3A%2F%2Fwww.solidworks.com%2Ffr&usg=AOvVaw2PKKzNpHSQdI9BvKXJUuLo&opi=89978449)**, pour réaliser chaque pièce de la borne. Les fichiers peuvent être trouvés sur le lien du drive. Pour ma part j'ai utilisé FreeCAD

![utilisation du logiciel de CAO](/assets/img/project/Borne_d_arcade/CAO.png)

- Découpez les pièces à l'aide d'une **[découpeuse laser**](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DrHq1XwIzPL4&psig=AOvVaw0GFboQfyNL2UuevHQNS55l&ust=1696636394385000&source=images&cd=vfe&opi=89978449&ved=0CBQQ3YkBahcKEwjAzuebjeCBAxUAAAAAHQAAAAAQCQ)**, ou d'autres solutions telles qu'une scie sauteuse ou une scie. Dans mon cas j'avais à disposition de la découpeuse laser et du logieciel de FAO "Laserbox". pour etre sur de nos calcules il faut en premier lieu un prototypage en carton.

![Prototypage de la Borne en carton](/assets/img/project/Borne_d_arcade/protocarton_borne.jpg)

- La disposition des **[boutons](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.amazon.com%2FButtons-EG-STARTS-Joystick-Raspberry%2Fdp%2FB01M2X88QP&psig=AOvVaw24R-zllYnmTKl9GBSw74hN&ust=1696636929855000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCLiRiZuP4IEDFQAAAAAdAAAAABAG)** et du **[joystick](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.amazon.com%2FButtons-EG-STARTS-Joystick-Raspberry%2Fdp%2FB01M2X88QP&psig=AOvVaw24R-zllYnmTKl9GBSw74hN&ust=1696636929855000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCLiRiZuP4IEDFQAAAAAdAAAAABAG)** est cruciale pour une utilisation confortable de la borne d'arcade. Il existe des **[schémas](https://pxlbbq.com/wp-content/uploads/2017/05/sega1_l.png)** pour indiquer la position idéale des boutons. Toujours avec un prototypage en carton ^^

![Personnalisation de la borne avec mario pixel](/assets/img/project/Borne_d_arcade/proto.jpg)

- Pour la partie électronique, utilisez un **écran d'occasion** et une **[Raspberry Pi 2+](https://www.raspberrypi.com/documentation/)** connectée aux boutons. *Attention: la taille de votre écran vas déterminer vos dimensions*

- La partie logicielle est plus complexe. Il faut installer la bonne version de **[Recalbox](https://www.recalbox.com/fr/)**. Pour ce faire, visitez le site web de Recalbox et créez soit une **[clé USB bootable](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiv97HRjuCBAxXOR6QEHZBPAUYQtwJ6BAguEAI&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DGcRBwI9-eug&usg=AOvVaw2VMXTMaAPA_Otew1gt-L4s&opi=89978449)**, soit une **[carte SD bootable](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiv97HRjuCBAxXOR6QEHZBPAUYQtwJ6BAguEAI&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DGcRBwI9-eug&usg=AOvVaw2VMXTMaAPA_Otew1gt-L4s&opi=89978449)**. *Attention: si vous utilisez un ordinateur pour faire fonctionner la borne, un environnement Linux est nécessaire*.

- Après avoir construit la borne, vous pouvez la personnaliser comme vous le souhaitez, que ce soit visuellement ou en modifiant la partie front de l'OS Recalbox. La personnalisation de Recalbox peut être réalisée en utilisant le **[scraping](https://www.youtube.com/watch?v=a8-XDy_tYAw)** pour les jeux ou en changeant le **thème Recalbox**. En ce qui concerne les jeux, je vous conseille de regarder directement des vidéos car il existe plusieurs façons d'avoir des jeux dans la console. 

![Borne en train de fonctionner](/assets/img/project/Borne_d_arcade/ingame.png)
![Borne en marche avec son créateur](/assets/img/project/Borne_d_arcade/borne-d-arcade.png)

- Et enfin profité, faite partager, ou faite payer mais attention c'est illégale ^^

![Borne en marche au salon du Safra numérique](/assets/img/project/Borne_d_arcade/Safra_numerique.png)


## Téléchargement des ressources 
> Vous pouvez vous aussi la réaliser sans rien faire avec tout les dossier qui sont ici: 

- [La Parties FAO](https://drive.google.com/drive/folders/1l8KBKS_DKK8M51PJvBYQ1OmmrbqSskoz?usp=drive_link) *sous freecad je precise*
- [La Parties Scraping](https://drive.google.com/drive/folders/1VqpI_UWtA0QQUX6-7rAunpzHCxvgmyDm?usp=drive_link)
- [La Parties OS recalbox](https://drive.google.com/drive/folders/1BNq80I9mQ7tGICTAPnmZjTvw8rT7d2Sf?usp=drive_link)

