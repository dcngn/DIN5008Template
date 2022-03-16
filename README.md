# Simple Latexvorlage DIN5008 mit Internetmarke im Brieffenster



## Einbindung der Internetbriefmarke

Um die Internetbriefmarke der Deutschen Post über Latex im Brieffenster einzubinden, wird ein einfacher \includgraphics-Befehl genutzt, der die Marke trimmt. 

Dazu benötigt man zuerst eine kompakte Version der Internetmarke. Diese erhält folgendermaßen während der Bestellung:

1. Die den Link "Absender und Empfänger bearbeiten" anklicken.
2. Keine Adresse eingeben.
3.  Mit "Adresse(n) übernehmen" bestätigen. 

Die generierte Postmarke dann im Latexordner speichern und mit dem Befehl \includepostage{relatier/pfad/zur/postmarke} vor der Empfängeradresse einbinden. 

Das Ganze funktioniert nur, so lange die Deutsche Post sich nicht entscheidet die Dimensionen der so generierten Postmarke zu ändern.
