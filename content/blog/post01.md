---
title: "Aggiornamento sito"
date: 2019-03-05T08:39:42+01:00
draft: false
tags: ["Web", "html", "Linux"]
categories: ["Tutorial"]
---
### Questa guida vuole semplificare il processo di upload di un sito realizzato con GitHub Pages, e Hugo WebDesign.

1. entrare nella cartella <username.github.io> e cancellarne il contenuto.

2. aprire un terminale e nella cartella "username.github.io" eseguire il comando:

   > git pull origin master

   Il quale consente di aggiornare il contenuto della cartella.

3. Entrare nella cartella "nomesito" ed eseguire il comando

   > hugo -d ../username.github.io/

   Per creare nella cartella "username.github.io" i file .html e .md necessari per il sito.

4. Entrare ora nella cartella "username.github.io" ed eseguire il comando:

   > git status

   Nel terminale apparirà un riassunto dei file da modificare nella repository.

5. Eseguire sempre nella stessa cartella il comando:

   > git add --all

   Per aggiornare i file contenuti nella repository.

6. Eseguire ora il comando:

   > git commit -m "Commento sull'update"

   Per dare un commento all'update fatto al sito.

7. Infine eseguire il comando:

   > git push origin master

   Per caricare i file nella repository. Verrà richiesto l'username e la password dell'account GitHub collegato.
