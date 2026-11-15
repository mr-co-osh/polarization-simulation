# Standards für alle Seiten dieses Repositorys

Stand: 15.11.2026 · gilt dauerhaft für jede bestehende und jede neue Seite.

**Hintergrund:** Die Seiten sind Unterrichtsmaterial für den Physikunterricht (Sekundarstufe I, Bremen), liegen öffentlich auf GitHub Pages (Konto mr-co-osh) und werden per Link an Schüler:innen weitergegeben.

## 1. Technik und Datenschutz
- Jede HTML-Seite beginnt mit:
  ```html
  <meta charset="utf-8">
  <meta name="robots" content="noindex, nofollow, noarchive">
  ```
- Nichts von fremden Servern laden: keine Google Fonts, keine CDNs, keine eingebetteten Videos oder Simulationen (YouTube, PhET, GeoGebra, LEIFIphysik usw.). Simulationen und Diagramme selbst bauen oder lokal ablegen, wenn die Lizenz das erlaubt. Externe Angebote höchstens als normaler Link, den man bewusst anklickt.
- Keine Anmeldung, keine Cookies, kein Tracking, keine Formulare, die Daten verschicken. Fortschritt und eingegebene Messwerte nur im Browser speichern (localStorage), mit try/catch.
- Kamera, Mikrofon oder Sensoren des Geräts nur nutzen, wenn die Auswertung vollständig im Gerät bleibt, und das auf der Seite erklären.

## 2. Personen
- Keine echten Namen, Fotos oder Messprotokolle von Schüler:innen auf den Seiten oder im Repository. Beispielnamen sind erfunden.
- Kein Name der Schule und keine Kontaktdaten, außer im Impressum.

## 3. Inhalte und Urheberrecht
- Erklärtexte, Aufgaben, Versuchsanleitungen, Abbildungen und Diagramme sind selbst erstellt. Nichts aus Schulbüchern, Arbeitsheften, Prüfungsaufgaben oder von Lernportalen übernehmen, auch nicht leicht umformuliert und nicht mit denselben Zahlen.
- Fotos von Versuchen, Geräten oder Personen nur, wenn die Lehrkraft sie selbst geliefert hat. Keine Bilder aus dem Netz, außer mit freier Lizenz und Lizenzangabe.
- Formeln, Naturkonstanten und Standardversuche sind frei nutzbar, die konkrete Darstellung fremder Quellen nicht.
- Fachlich korrekt bleiben: Einheiten, Formelzeichen und gerundete Werte prüfen, Rechenwege nachrechnen.
- Sicherheit: Versuche für zu Hause nur, wenn sie ungefährlich sind. Kein Netzstrom, keine offenen Flammen, keine Laser, keine gefährlichen Stoffe. Sonst klar als Schulversuch unter Aufsicht kennzeichnen.

## 4. Seitenfuß auf jeder Seite
- Satz: „Eigenes Unterrichtsmaterial. Kein offizielles Material der Bremer Bildungsbehörde. Dein Fortschritt wird nur in diesem Browser gespeichert.“
- Aufklappbarer Datenschutzhinweis mit den Punkten: keine Datensammlung, Speicherung nur im Browser, Hosting über GitHub Pages (GitHub, Inc., USA, verarbeitet die IP-Adresse), nichts von fremden Servern, Rechte nach DSGVO, Verantwortlicher.
- Impressum: Platzhalter vorsehen. Die Angaben liefert die Lehrkraft nach. Nichts erfinden.

## 5. Arbeitsweise
- Vor jeder Änderung den aktuellen Stand holen (`git pull`), nie mit force pushen. Andere Sitzungen ändern dieselben Repositories.
- Zuerst alle bestehenden Seiten gegen diese Regeln prüfen und eine kurze Liste der Abweichungen vorlegen. Erst nach Okay ändern. Inhaltliche Aufgaben nicht ungefragt umschreiben.
- Nach jeder Änderung die Seite im Browser laden und prüfen, dass keine Anfrage an einen fremden Server geht.
