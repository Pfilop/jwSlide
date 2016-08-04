# jwSlide

## About

LIES- &amp; Lied-Texte sollen dynamisch aus der EPUB importiert werden können. (unzip)

Importierte Publikationen werden global gespeichert; Katalog auf User-Basis in der MongoDB gespeichert.

Textausgaben werden via Socket bzw DDP an alle weiteren - nach dem Ersten - Clients gesendet (Zweites F11-Browserfenster für Beamer-Präsentation).

Zu lange Texte (Liedtexte) werden mittels Links Maustaste oder Leertaste geblättert.

## Tools

Folgende Pakete werden benutzt

- `Meteor` MEAN-ähnlicher Stack - beinhaltet Templating-Engine, MongoDB, node.js (-server), HTTP, etc
- `Angular2` Bessere Templates und zusammen mit Meteor ein 3-way-data-binding
- `SASS` compiler und alles ist bei meteor schon an Bord - Grunt, Gulp und Co werden nicht gebraucht
- `TypeScript` .. warum auch nicht

## Installation

Da alles bei meteor on board ist, reicht es dieses zu installieren.

PHP, Apache, MySQL, Java oder Sonstiges wird natürlich nicht benötigt.

Weitere projektbezogene Pakete und Module werden dann eh über
` $ meteor ` bzw ` $ meteor npm install ` geholt.

Der Server wird dann auch über `$ meteor` gestartet.
