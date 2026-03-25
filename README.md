# ProzessiereFasP
Dieses Projekt dient zum Weiterverarbeiten von Expositions-Geodaten für epidemiologische Studien; z.B. die GHS.
Dabei wird ein Bericht geschaffen, der die Verabeitung illustriert, geographische und quantitative Zusammenhänge zeigt.
## Organisation
- Der Quellcode ist im qmd-File. Das Kürzel kommt von Quarto, in gewisser Weise ein Nachfolger von RMarkdown. 
- Die Eingabe sind Geodaten (sind nicht im Github-Projekt enthalten; u.a. da sie zu groß sind)
- Die Ausgabe erfolgt zum einen
-     - als Geodaten (sind nicht im Github-Projekt enthalten; u.a. da sie zu groß sind)
-     - als Bericht in html. (ist enthalten)
## Arbeitsschritte
- Lade Fassadenpunkte, die aus der Lärmkartierung, z.B. Straßenlärmkartierung des LfU RLP stammen
- lade Emissionslinien, z.B. das Verkehrsmodell
- Füge zu den Fassadenpunkten die Abstände zu verschiedenen Arten der Straßen hinzu.
- Danach sollen die Fassadenpunkte wieder exportiert werden und zum weiternutzen bereit sein.
