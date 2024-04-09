# Git Cheatsheet

`ls` list all items in folder

`cd <folder-name>` change directory / gehe zu Ordner

`cd ../` gehe in übergeordneten Ordner

`cd` go to Root / Hauptordner

`clear` Terminal leeren (vorheriges wird nicht gelöscht, nur nach oben geschoben)

`mkdir <folder-name>` Make directory / Ordner erstellen

`touch <file-name.ending>` Datei erstellen

`rm <file-name.ending>` remove file / Datei löschen

`rm <folder-name> -rf` remove recursive force / löscht Ordner inklusive Inhalt

`mv <file-name.ending> <./path/folder-name>` move / verschiebt Datei in Ordner

`mv <file-name.ending> <new-file-name.ending>` Datei umbenennen

`open .` öffnet aktuellen Ordner im OS

`cat <file-name.ending>` öffnet Datei im Terminal

`code .` öffnet Folder in Editor / VS Code

`code <file-name.ending>` Öffnet Datei in Editor / VS Code

`git init` Repository erstellen / initialisieren

`rm -rf .git` Git Repo wird entfernt / Ordner wird wieder normaler Ordner

`main >` man befindet sich auf main branch

`.gitignore` Datei in der alle Dateien aufgelistet sind, die nicht veröffentlicht werden sollen

`git status` zeigt des Status der Dateien an

`git add <file-name.ending>` Datei wird gestaged

`git add .` alle Dateien werden gestaged

`git commit -m "<Message>"` Alle staged Dateien werden comitted

`git log` commit Hostorie

`git log --oneline` Historie untereinander anzeigen

`git remote -v` Verknüpfung wird angezeigt

`git remote add origin <SSH-Key>` Verknüpfung zu Github-Repository mit entsprechenden SSH-Key herstellen

`git push -u origin main` Push all commits to repo (-u = upstream // macht man beim ersten Mal)

## Branch & PRs

`git switch -c <branch-name>` Branch erstellen und direkt reinwechseln (Name z.B. navigation etc.) (-c = create)

`git switch <branch-name>` auf existierenden Branch switchen

`git switch -` zum letzten Branch switchen

`git push -u origin <branch-name>` Push branch first time

`git branch` zeigt alle Branches

`git branch -d <branch-name>` Branch löschen (-d = delete)
