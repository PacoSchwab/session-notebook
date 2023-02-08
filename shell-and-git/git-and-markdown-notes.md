Shell / Terminal: tab Autovervollständigung, pwd: Ordnerübersicht, ls: Unterordner, ls -l: detaillierte Ansicht, cd: Ordnerwechsel, ..: ein Ordner nach oben, ../xxx: in entsprechenden Ordner gehen, cd ~: ins Nutzerverzeichnis zurück gehen, mkdir xxx: makedirectory xxx, touch xxx: Dateierstellung (z.B. touch README.md index.html styles.css scripts.js) bzw. modified date auf aktuellen Zeitpunkt setzen (Datei berühren), Pfeiltaste nach oben/unten: durch letzte Befehle wechseln, ctrl+u: löscht komplette Zeile, rm: Datei endgültig löschen, rm-r: komplettes Verzeichnis löschen, rm -rf: alles kann gelöscht werden ohne Sicherheitsabfrage, rm -rf /: komplette Festplatte löschen (/ = absolutes Verzeichnis, Grundverzeichnis), mv: move (Datei verschieben) --> z.B. mv scripts.js files/scripts.js (kann währenddessen auch umbenannt werden z.B. mv scripts.js files/superscripts.js oder mv scripts.js superscripts.js, cat: in Datei reinschauen um uns eine Ausgabe davon geben zu lassen, cd ohne tilde bringt zurück zum Hauptverzeichnis, cd - bringt zurück zum am letzten verwendeten Ordner

In .gitignore-Datei die Dateien rein schreiben, die nicht ins Repo sollen, z.B. .DS_Store

weitere Commands:

top (ressourcenfressendste Anwendungen anzeigen), man (Anleitung für bestimmte Befehle, z.B. "man git")

in visual studio code (preview von md dateien anzeigen)

cmd+shift+p in visualstudio für command list oder oben rechts live preview klicken

Datei erstellen und direkt beschriften: echo "abcde" >> testdatei.md (>> um Text an evtl. bestehenden dran zu hängen und > um alten Text zu überschreiben)

git remote set-url origin git@github.com:{USERNAME}/{PROJECTNAME}.git um http zu ssh zu ändern

"open ." Datei im Finder öffnen

git switch -c xyz: neuen Branch erstellen (c = create)
git switch main: zurück zum main branch
git switch xyz: wechselt zum entsprechenden Branch
"code .": Öffnet aktuelles Verzeichnis in visualstudio code

cmd+j in visualstudio code: Terminal öffnen

cmd + k: löschen in Terminal

git pull -r: falls remote und lokal nicht synchron sind, sondern an beiden gearbeitet wurde, anstatt rechtzeitig zu pushen/pullen

git branch -D xyz: Branch-Label lokal löschen (nicht so wichtig, da es kaum Ressourcen frisst)

git fetch --all: zeigt alle Neuigkeiten, auch neue Branches an // git branch -a: zeigt auch remote branches an, die noch nicht lokal gepulled wurden

git add -A: alles adden

More infos:

"--set upstream" Abkürzung für "-u"

pull request in github löst merge in git aus

LGTM = Looks good to me