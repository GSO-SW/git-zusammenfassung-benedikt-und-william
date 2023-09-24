# gitStarted
In diesem Repository sollen Sie die ersten Schritte mit git und gitHub durchführen.

## Aufgaben :dart:
1. Vervollständigen Sie Liste der bekannten git-Befehle!
2. Vervollständigen Sie **arbeitsteilig** die Beschreibungen der git-Befehle! (Sie können die Hilfe via `git help <command>` aufrufen
4. Bilder sollten nicht in git gespeichert werden. Löschen Sie die Datei RubberDuck.png und puschen Sie den neuen Commit!
2. Ergänzen Sie die Liste um weitere git-Befehle, die Sie heute kennen gelernt haben! (setzen Sie die Befehle aus 1. ein)
3. Nutzen Sie [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), um dieses Dokument zu formatieren.
4. ~~Erledigtes können Sie abhaken ;)~~

Schon fertig? Beantworten Sie diese Fragen:
1. Wie setzt man eine .gitignore-Datei ein?
2. Wann sollte ein Commit durchgeführt werden? Was macht eine "gute" Commit-Message aus?

## git-Befehle
1. `git clone <url>` kopiert ein vorhandes Repository von einer url auf die Festplatte
2. `git push` schiebt Änderungen auf das repository hoch / Wird zur arbeit zwischen local und remote benutzt und macht Veränderungen entgültig aus einer Kombination von "git merge" und "git fetch"
3. `git pull` du ziehst dir daten vom repository runter / zieht den letzten commit aus einem remote repository zur Bearbeitung im local
4. `git commit` erstellt einen neuen punkt / Veränderungen an einem commit aus einem Repository
5. `git fetch` download von anderen repositorys / Wird benutzt um commits aus repositorys zu holen
6. `git merge` fügt mehrere branches zusammen / Fügt zwei commits zusammen
7. `git rebase` mehere commits schnell zusammen fügen
8. `git branch` erstellt eine Verbindung zwischen zwei punkten
9. `git add -u` Wird genutzt um gelöschte Datein in die staging area hinzuzufügen um diese anschließend zu commiten
- Gelöschte Datein werden nicht mit einem `git add` in den commit mitgenommen
<<<<<<< HEAD
- `git check-pick` Wird benutzt um einen einzelnen commit zu picken und diesen in einem commit zuverewigen
- `git add` fügt die bevorstehenden Änderungen in die staging area
- `git revert` macht den letzten commit Rückgängig
- `git reset` Setzt den commit auf einen anderen commit zurück
=======
- `git reset` lokale Änderungen auf den Stand eines bestimmmten Git Repositorys zurücksetzten
>>>>>>> 8c13c81043803498e980291337ff0250649969a7


## .gitignore-Datei erstellen
- Um eine Gitignore-Datei zu erstellen, legst du eine Textdatei mit dem Namen .gitignore im Hauptverzeichnis deines Git-Repositorys an

## Wann sollte ein commit durchgeführt werden und was macht einen "guten" aus
- `Wann?` Wenn große Änderungen am vorgenommen werden die vom letzten commit abweichen 
- `was macht eine gute commit message aus?` Informierend über die Änderungen, möglichst kurz und verständlich

## Wann sollte ein Commit durchgeführt werden? Was macht eine "gute" Commit-Message aus? 
- `Ein commit sollte durchgeführt werden wenn man eine Änderung im lokalen repository durchführen möchte. Eine gute Commit Message beschreibt den commit so gut wie möglich und übersichtlich`





