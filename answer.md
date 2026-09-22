\# Kontrollfragen



\## 1. Was ist der Unterschied zwischen Working Directory, Staging Area und Repository?



Das Working Directory enthält die Dateien, an denen ich aktuell arbeite.



Die Staging Area enthält die Änderungen, die ich mit `git add` für den nächsten Commit ausgewählt habe.



Das Repository enthält die Änderungen, die bereits mit einem Commit dauerhaft gespeichert wurden.



\## 2. Woran erkennst du, ob ein Merge Fast-Forward war?



Beim Merge zeigt Git die Meldung `Fast-forward` an.



Außerdem wird kein zusätzlicher Merge-Commit erstellt.



\## 3. Warum kann git merge --ff-only manchmal fehlschlagen?



Der Befehl schlägt fehl, wenn auf beiden Branches unterschiedliche neue Commits entstanden sind.



Dann kann Git den Branch nicht einfach vorspulen.



\## 4. Was ist der Vorteil, Änderungen zuerst auf einem Branch wie dev zu machen?



Man kann Änderungen getrennt vom Hauptbranch entwickeln und testen.



Der Hauptbranch bleibt dabei zunächst unverändert.



\## 5. Mit welchem Befehl siehst du den aktuellen Branch?



`git branch --show-current`



Alternativ zeigt auch `git branch` den aktuellen Branch mit einem Sternchen an.



\## 6. Mit welchen Befehlen machst du Änderungen sichtbar und dauerhaft?



Mit `git add` werden Änderungen zur Staging Area hinzugefügt.



Mit `git commit` werden diese Änderungen dauerhaft im Repository gespeichert.

