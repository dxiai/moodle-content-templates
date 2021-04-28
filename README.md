# HTML-Vorlagen für Moodle Materialien

Hilfreiche Vorlagen zur Gestaltung von Inhalten unter Moodle. 

Diese Vorlagen verwenden wir in unseren Moodle Kursen im Modul **Daten und Information** an der ZHAW. Sie sind an unsere Bedürfnisse ausgerichtet und entsprechend unvollständig. 

Wenn weiter Elemente oder Anpassungen gewünscht sind, bitte ein neues [Issue](https://github.com/dxiai/moodle-content-templates/issues) erstellen und genau beschreiben was fehlt oder angepasst werden soll.

Diese Vorlagen basieren auf [Bootstrap 4](https://getbootstrap.com/docs/4.5/getting-started/introduction/) und den [font awesome 4.7 Icons](https://fontawesome.com/v4.7.0/icons/). Diese Versionen werden von Moodle direkt unterstützt.

Die Vorlagen basieren auf den responsiven Layouts von Bootstrap, so dass sie auch auf Mobilgeräten gut aussehen. 

## Verwendung

Alle Element sind also HTML-Code gestaltet. Sie eignen sich für Textfelder, Textseiten und Beschreibungen. Dazu muss in den HTML-Modus des Moodle-Editors gewechselt werden.

Prinzipiell können die Vorlagen auch in Tests eingesetzt werden, aber dort muss die spezielle Formiertung beachtet werden. Manche Styles sind dort nämlich unsichtbar. 

Praktisch alle Elemente müssen angepasst werden.

Wenn schon Inhalte existieren, dann können diese an den entsprechenden Stellen von den Elementen der Vorlangen "eingerahmt" werden. 

Wenn die HTML-Blöcke auf Textseiten eingebettet werden, dann muss im Moodle-Editor darauf geachtet werden, dass man sich einen kleinen Hilfstext oben und unten anlegt, denn sonst ist das weitere Bearbeiten schwierig und führt zu unerwünschten Ergebnissen. 

### Markdown

Alle Vorlagen sind für die Nutzung mit Markdown vorbereitet.

Falls Inhalte in Markdown vorliegen können diese eingefügt werden, wenn als Texteditor "Unformatiert" und dann als Formatierung "Markdown" ausgewählt wurden.

## Elemente

### Ein-spaltige Elemente

* [Pfeil nach unten](html/1c_info_large_arrow_down.html)

#### Highlight Block 

Es gibt alle Vorlagen als volle Breite und als 2/3 Variante.

* [Warnung (Gelb) ganze Breite](html/1c_block_warning.html)
* [Warnung (Gelb) 2/3 Breite](html/1c_block_warning_narrow.html), zentriertes Symbol

* [Warnung (Rot) ganze Breite](html/1c_block_danger.html)
* [Warnung (Rot) 2/3 Breite](html/1c_block_danger_narrow.html), zentriertes Symbol

* [Info (Blau) ganze Breite](html/1c_block_definition.html)
* [Info (Blau) 2/3 Breite](html/1c_block_definition_narrow.html), zentriertes Symbol

* [Erfolg (Grün) ganze Breite](html/1c_block_success.html)
* [Erfolg (Grün) 2/3 Breite](html/1c_block_success_narrow.html), zentriertes Symbol

#### Buttons für Links

**Achtung**: Alle Schalter (Buttons) sind Links. D.h. Es muss die richtige URL zum Inhalt angepasst werden werden. In den Vorlagen sind diese mit `DOWNLOAD_LINK` bzw. `MOODLE_LINK` gekennzeichnet. 

* [Download-Link (Blau) mit Download-Icon](html/1c_button_download.html)
* [Inhalts-Link (Grün) mit Datei-Icon](html/1c_button_content.html)

### Zwei-spaltige Elemente

**Achtung**: Die rechte Spalte enthält einen Link, der angepasst werden muss. In den Vorlagen sind diese mit `LINK_ZUM_MEETING_RAUM` gekennzeichnet. 

* [Infoblock (2/3) mit Link (1/3)](html/2c_block_info_link_green.html) (für Videokonferenzen) Grün
* [Infoblock (2/3) mit Link (1/3)](html/2c_block_info_link_orange.html) (für Videokonferenzen) Gelb

### Flex (Mehrspaltige) Layouts (TODO)

Diese Elemente sind noch in Arbeit.

Flex-Elemente nutzen das [flexible Layout](https://getbootstrap.com/docs/4.5/utilities/flex/) von Bootstrap. 

#### Block definition

* linksbündige Darstellungen
* rechtsbündige Darstellungen
* zentrierte Darstellungen

#### Elemente

* Element für einspaltige Darstellung
* Element für 2/3 Darstellung
* Element für 1/3 Darstellung
* Element für 3-Spalten Darstellung
* Element für 4-Spalten Darstellung
