# INTERLIS Modelle im Auftrag der Landesgeologie

## Deep Wells - Bohrungen Tiefer 500

Entspricht https://map.geo.admin.ch/#/map?lang=en&center=2684011.42,1268430.43&z=6.282&bgLayer=ch.swisstopo.pixelkarte-farbe&topic=ech&layers=ch.swisstopo.geologie-bohrungen_tiefer_500@features=30&featureInfo=default

GeoPackage Bezug hier https://data.geo.admin.ch/browser/index.html#/collections/ch.swisstopo.geologie-bohrungen_tiefer_500/items/geologie-bohrungen_tiefer_500?.language=en

Es wurde für sämtliche Attribute `TEXT` als Typ gewählt, denn die Dates haben Platzhalter (e.g. `XX.10.2020`) und die Zahlenwerte teilweise Hochkomma und Zusatzzeichen (e.g. `153'093 (?)`).

Dieses Modell würde alle Daten, die aktuell im GeoPackage vorhanden sind beinhalten. Auf dem WebGIS sind nur Teile davon visualisiert (alle die mit einem `!! Kommentar`). Ich nehme an, da die Sprache aktuelle so geregelt wird, dass nur ein Teil der Spalten angezeigt wird, würden die irrelevanten Attribute einfach nicht angezeigt, beim Datenbezug aber enthalten sein.

Ich habe mal die Attributnamen aus dem GeoPackage übernommen (ausse `Temp_°C`, weil das Grad-Zeichen nicht erlaubt ist im INTERLIS). Diese Namen könnten noch verständlicher oder einheitlicher sein. Die Frage ist aber, ob diese meinerseits "verbessert" werden sollen, oder besser in ihrer Ursprungsform gehalten werden.

Anosonsten wäre es das schon. Es ist wirklich ein sehr einfaches Modell, aber das ist nicht unüblich für Publikationsmodelle.
