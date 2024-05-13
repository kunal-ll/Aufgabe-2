# Git-Workshop Aufgabe-2

**Aufgabe 2 - Branching und Merging Steckbrief**
Bitte clont das Projekt und bearbeitet die folgende Aufgabe.


**Aufgabe:**
1. **Branch 'head-section' erstellen:**
   - Erstellen Sie einen neuen Branch namens 'head-section'.
   - Fügen Sie den folgenden Code in den `<head>`-Bereich der HTML-Datei ein und passen Sie ihn an:
   ```html
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Steckbrief von Person</title>
   <style>
       body {
           font-family: 'Arial', sans-serif;
           background-color: #f9f9f9;
           margin: 20px;
           color: #333;
       }
       .profile {
           background: white;
           border: 1px solid #ccc;
           border-radius: 10px;
           padding: 20px;
           max-width: 600px;
           margin: auto;
           box-shadow: 0 2x 10px rgba(0,0,0,0.1);
       }
       h1 {
           color: #0077cc;
       }
       .details {
           margin-top: 20px;
       }
       .details p {
           line-height: 1.6;
           font-size: 16px;
       }
       .profile img {
           width: 100%;
           height: auto;
           border-radius: 10px;
       }
       .attribute {
           font-weight: bold;
       }
   </style>
   ```

2. **Branch 'body-section' erstellen:**
   - Wechsele in die main Branch zurück
   - Erstellen Sie einen neuen Branch namens 'body-section'.
   - Fügen Sie den folgenden Code in den `<body>`-Bereich der HTML-Datei ein und passen Sie ihn an:
   ```html
   <div class="profile">
       <img src="pfad/zum/bild.jpg" alt="Bild von Person">
       <h1>Name der Person</h1>
       <div class="details">
           <p><span class="attribute">Alter:</span> 30 Jahre</p>
           <p><span class="attribute">Beruf:</span> Softwareentwickler</p>
           <p><span class="attribute">Wohnort:</span> Berlin, Deutschland</p>
           <p><span class="attribute">Interessen:</span> Lesen, Wandern, Programmieren</p>
           <p><span class="attribute">Kurzbiografie:</span> Geboren und aufgewachsen in Hamburg, hat die Person Informatik studiert und arbeitet seit 5 Jahren als Softwareentwickler in Berlin. In der Freizeit geht sie gerne wandern und beschäftigt sich mit Open-Source-Projekten.</p>
       </div>
   </div>
   ```

4. **Branch 'footer-section' erstellen:**
   - Wechsele in die main Branch zurück
   - Erstellen Sie einen neuen Branch namens 'footer-section'.
   - Fügen Sie den folgenden Code in den `<footer>`-Bereich der HTML-Datei ein und passen Sie ihn an:
   ```html
   <footer>
       <p>Kontakt: <a href="mailto:email@beispiel.com">email@beispiel.com</a></p>
       <p>&copy; 2023 Name der Person. Alle Rechte vorbehalten.</p>
   </footer>
   ```

6. **Mergen der Branches:**
   - Wechseln Sie zurück zum Hauptbranch und führen Sie die Branches der Reihe nach zusammen (`git merge head-section`, `git merge body-section`, `git merge footer-section`).
   - 
 7. **Löschen der Branches:**
   - Lösche 'head-section', 'body-section' und  'footer-section'.

**Hinweise zum Mergen:**
- Überprüfen Sie nach jedem Merge die Funktionalität der gesamten Seite.
- Lösen Sie eventuelle Merge-Konflikte sorgfältig auf.

Diese strukturierte Aufgabenstellung ermöglicht es den Workshop-Teilnehmern, ein umfassendes Verständnis von Git Branching und Merging zu entwickeln, während sie gleichzeitig praktische Erfahrungen mit der Versionierung und Zusammenführung von Code sammeln.
