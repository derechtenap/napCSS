# napCSS
*Kleines Framework - Geschrieben in SCSS*


<p align="center">
  <img src="https://raw.githubusercontent.com/derechtenap/napCSS/master/docs/static/napcss-logo.png" alt="napCSS">
</p>


> Currently, this project is exclusively available in **German**.
### Übersicht
**Aktuelle Version: 0.01**

Dieses Framework wird in SCSS geschrieben. Alle variablen Werte befinden sich in der `_var.scss`. Dies ermöglicht es, das Framework persönlich anzupassen. Durch die Anpassung müssen allerdings die SCSS-Dateien in CSS umgewandelt werden. Dies geht am einfachsten über den Live SASS Compiler. Das fertige Framework befindet sich im `release`-Ordner.

**Anregungen, Ideen und Fehler bitte über die 'Issues'-Funktion von GitHub.**
### Struktur
```
|
│   README.md
│   .gitigonore  
│   .gitattributes
|
└─── scss
│   │   nap.scss
│   │   _var.scss
│   │   _layout.scss
|   |
│   └─── misc
│   |   │   _spacer.scss
│   |   │   _code.scss
|   |
|   └─── util
│       │   _text.scss   
|
└─── docs
|
└─── dist
|   └─── release
|
```
### Funktionen
Alle aktuellen Funktionen können in der Dokumentation (`docs/ger/index.html`) eingesehen werden.
### Zukünftige Funktionen
Dieser Funktionen sind für die nächsten Versionen geplant:

**0.0.2**
- Flex Grid-System
- Border Utils
- Background Utils

**0.0.3**
- Darkmode
