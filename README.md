
Hintergrund
===========

Diese Slides haben zum Ziel Einsteigern einen Einblick in die agile Softwareentwicklung zu vermitteln.
Sie sind bewusst etwas textlastiger als nötig gehalten um die wichtigsten Inhalte auch ohne eine persönliche Präsentation zu transportieren.

Verbessserungs-, Erweiterungsbeiträge nehme ich gerne an, Pull Requests sind sehr willkommen.


Entwickeln
===========

 * Latex installieren
   ```
   apt-get install texlive-fonts-extra texlive-fonts-recommended texlive-base texlive-binaries texlive-extra-utils \
    texlive-font-utils texlive-fonts-recommended texlive-fonts-recommended-doc texlive-generic-recommended \
    texlive-lang-german texlive-latex-base texlive-latex-base-doc texlive-latex-recommended texlive-latex-recommended-doc \
    texlive-pictures texlive-pictures-doc texlive-pstricks texlive-pstricks-doc texlive-latex-extra
   ```
 * Editieren und kompilieren
   ```
   # Editieren und Ausführen
   vim -p src/parts/*
   ./process dev

   # Geöffnet lassen, aktualisiert sich automatisch
   evince tmp/vortrag.pdf &

   # Editieren und Ausführen
   ./process dev
   ```
 * Finale Version erstellen
   ```
   ./process final
   ./process clean
   git commit -m "<Kommentar>" -a
   ```


Nutzungsrechte bzw. Lizenz
==========================

Die Slides sind Opensource und stehen unter der BDS3 Lizenz (siehe "LICENCE")
Bedingt durch die BDS3 Lizenz kann diese Version vorbehaltslos auch in Unternehmen genutzt und verändert werden.

Die genutzten Grafiken sind meines Wissens frei von rechten Dritter.
