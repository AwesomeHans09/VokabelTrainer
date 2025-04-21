---
type: ProjectLayout
title: Vokalen Trainer
date: '2025-04-21'
client: ''
description: ''
featuredImage:
  type: ImageBlock
  url: /images/e.jpg
  altText: altText of the image
  caption: Caption of the image
  elementId: ''
bottomSections:
  - type: TextSection
    title: The Section Title
    text: |+
      ```
      </head>
      <body>
          <h1>Vokabeltrainer</h1>
      ```

          <div id="neueVokabelnDiv">
              <h2>Neue Vokabeln hinzufügen</h2>
              <label for="vokabelEingabe">Englische Vokabel:</label>
              <input type="text" id="vokabelEingabe" placeholder="Englisch">
              <label for="uebersetzungEingabe">Deutsche Übersetzung:</label>
              <input type="text" id="uebersetzungEingabe" placeholder="Deutsch">
              <button id="vokabelHinzufuegenButton">Vokabel hinzufügen</button>
              <button id="startButton">Vokabeltraining starten</button>
              <ul id="vokabelListe"></ul>
          </div>

          <div id="pruefungsDiv">
              <p id="wortAusgabe"></p>
              <input type="text" id="eingabeFeld" placeholder="Deine Antwort">
              <div style="display: flex;">
                  <button id="pruefenButton">Prüfen</button>

              </div>
              <p id="punkteAnzeige"></p>
              <p id="feedbackAusgabe"></p>
          </div>

      </body>
      </html>

    colors: colors-a
    variant: variant-a
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        textAlign: left
metaTags: []
colors: colors-b
---
Vokaleb Trainer

