# Merkzettel-Git-GitHub
Kleine Aufgaben und Beschreibungen dazu, wie man ein repositiry erstellt, bearbeitet und aktualisiert 

## Repository erstellen
**Aufgabe 1:** erstelle ein Repository.

**Lösung:**
1. Gehe auf GitHub in deinem Profil auf das + und gehe auf "New Repository".
2. Benenne dein Repository und füge eine kleine Beschreibung hinzu
3. Wähle "Initialize this repository with a README" aus
 
**Tipp:** wähle einen kurzen und prägnanten Namen.

## Bearbeitungen deines Projektes
**Aufgabe 2:** nehme Änderungen in deiner Datei vor.

**Lösung:**
1. Clone dein Repository auf deinen lokalen PC. Kopiere dazu die URL von Github und öffne Git Bash. Mit dem Befehl `git clone [URL]` hast du das Repository auf deinem PC lokal gespeichert.
2. Bearbeite die README.md in dem du die Datei auf IntelliJ öffnest.
3. Speichere deine Änderungen.

Nun musst du die Änderungen wieder auf GitHub hochladen. um das tun zu können, musst du die Datei aber ersteinmal für den Push vorbereiten.

## Commiten und Mergen
**Aufgabe 3:** Commite und Merge ggf. deine Änderungen.

**Lösung:** 
1. Bevor du deine Änderungen commitest, schaust du dir am besten nochmal den Status deines aktuellen Repositorys an. Gebe dazu `git status`
in der Kommandozeile an. Dir wird nun angezeigt, welce Datein geändert wurden und welche Änderungen noch nicht erfasst sind.
2. führe nun einen Commit durch. Dies geschieht über den Befehl `git commit (ggf. Name der Datei) -m "Kommentar zur Änderung"`.
3. Führe nun einen Pull durch, indem du `git pull` eingibst. Falls es einen Konflikt mit anderen Bearbeitungen gibt, die auch hochgeladen werden sollen, wird das nun angezeigt.
4. im Konfliktfall, wirst du an dieser Stelle mergen müssen. 
Öffne dazu in IntelliJ VCS > Git > Merge Changes... . Nun kannst du alle verschiedenen zu mergenden Versionen sehen und bearbeiten, wie du es am Ende haben möchtest.

## Pushen
**Aufgabe 4:** Lade deine Änderungen wieder hoch.

**Lösung:**
1. mit dem Kommando `git push` lädst du deine Änderungen wieder hoch. 
2. Gebe deinen Username und Passwort von GitHub ein und deine Änderungen sollten nun online sein.