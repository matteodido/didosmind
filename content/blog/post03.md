---
title: "Setup i3wm su nuova macchina"
date: 2019-03-07T11:20:42+01:00
draft: false
tags: ["i3wm", "code", "Linux"]
categories: ["Tutorial"]
---

### Installazione di i3wm su una nuova macchina linux

Programmi necessari per l'installazione (consigliato installarli prima di i3wm):

* Feh
* Blueman
* xbacklight
* gtk-theme
* lxappearance

#### Installazione e setup di i3wm:

1. Installare i3wm da terminale con il seguente comando:

   >  sudo apt-get i3wm

   Chiudere la sessione e rientrare selezionando i3wm come Desktop Enviorment.

2. Creare i file i3status.conf, config e lock.sh all'interno della cartella /home/"username"/.config/i3/ e copiare al loro interno il testo dei file sotto:

   > [config](/links/configFile/config) [i3status.conf](/links/configFile/i3status.conf) [lock.sh](/links/configFile/lock.sh)

3. Scaricare un immagine di sfondo (in questo [link](https://drive.google.com/open?id=1Z2EBdSFiUz_C5CmxwGl_1WtqOzV0GK4f) lo sfondo dello screenshot), rinominarlo "t.jpg" e posizionarlo nella cartella Scaricati del sistema.

4. Scaricare il tema del sistema da questo [link](https://drive.google.com/open?id=1IQaocurM7_RhX9q0LIvm-OlRzX1pb2Id) e copiarlo nella cartella /usr/share/themes.

5. Scaricare i3-gapps e seguire le indicazioni della pagina GitHub per l'installazione e la configurazione.



