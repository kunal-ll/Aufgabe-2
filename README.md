# Git-Workshop Aufgabe-2

**Aufgabe 2 - Branching und Merging Steckbrief**
Bitte clont das Projekt, navigiert zum Ordner und bearbeitet die folgende Aufgabe.
   ```sh
   git clone https://github.com/kunal-ll/Aufgabe-2.git
   cd Aufgabe-2
   ```
**Aufgabe:**
1. **Branch 'head-section' erstellen:**
   - Erstelle einen neuen Branch namens 'head-section'.
   - Fügen den folgenden Code in den `<head>`-Bereich der HTML-Datei ein und passe ihn an:
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
   - Comitte die Änderungen
     
2. **Wechsele in die main Branch zurück und erstelle Branch 'body-section':**
   - Wechsele in die main Branch zurück
   - Erstellen einen neuen Branch namens 'body-section'.
   - Füge den folgenden Code in den `<body>`-Bereich der HTML-Datei ein und passe ihn an:
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
   - Comitte die Änderungen
     
4. **Wechsele in die main Branch und erstelle Branch 'footer-section':**
   - Wechsele in die main Branch zurück
   - Erstelle einen neuen Branch namens 'footer-section'.
   - Füge den folgenden Code in den `<footer>`-Bereich der HTML-Datei ein und passen ihn an:
   ```html
    <p>Kontakt: <a href="mailto:email@beispiel.com">email@beispiel.com</a></p>
    <p>&copy; 2024 Name der Person. Alle Rechte vorbehalten.</p>
   ```
   - Comitte die Änderungen
     
6. **Mergen der Branches:**
   - Wechseln zurück zum Hauptbranch und führen die Branches der Reihe nach zusammen (`git merge head-section`, `git merge body-section`, `git merge footer-section`).
     
 7. **Löschen der Branches:**
   - Lösche 'head-section', 'body-section' und  'footer-section'.
