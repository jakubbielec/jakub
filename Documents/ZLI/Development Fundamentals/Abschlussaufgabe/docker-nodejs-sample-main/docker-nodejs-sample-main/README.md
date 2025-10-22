# **Installation des Projekts**

    (Erstellen einer ToDo-Applikation mit Markdown, Git, GitHub und Docker)

---
---

- ## **Anleitung:**

---

- ### *Klonen des Repositories:*

   Als erstes muss man ein **Fork** erstellen.
   Dass mach man indem man, oben rechts auf *"Fork"* drückt.

---

- ### *Installation der notwendigen Pakete:*

   Als nächstes muss man auf *"Code"* drücken und dann auf *"Download ZIP"*.
   Dann kann man auswählen, wo die **ZIP-Datei** geöffnet werden soll.

---

- ### *Docker-Konfiguration und -Installation:*

   Als erstes muss man *(im Explorer)* in den Projektordner rein und oben in der Taskleiste *"cmd"* schreiben.
   Dann geht das **CMD** auf und man muss folgendes schreiben:

        git clone <https://github.com/benutzername/repo-name.git>

   *(mit eigenen Daten ausfüllen)*

        cd ordnername

   *(mit eigenen Daten ausfüllen)*

        git remote -v

   Danach kann man direkt im *CMD* **Docker** öffnen:

        docker init

   Als nächstes werden viele Fragen gestellt. Diese soll man wie folgt beantworten:

        ? What application platform does your project use? Node
        ? What version of Node do you want to use? 18.0.0
        ? Which package manager do you want to use? npm
        ? What command do you want to use to start the app: node src/index.js
        ? What port does your server listen on? 3000

   Um die Applikation zu starten, soll man als erstes im **CMD** bleiben.

---

- ### *Starten der Applikation in einem Docker-Container:*

   Um die Applikation zu starten kann man als erstes das eingeben:

        docker compose up --build

   Die Seite kann unter diesem Link gefunden werden: [localhost:3000/](http://localhost:3000/)

   Um die Applikation im Hintergrund laufen zu lassen, kann man das eingeben:

        docker compose up --build -d

   So kann man die Applikation stoppen und fortfahren:

        docker compose stop
        docker compose start

---

#### *Das war's!*
