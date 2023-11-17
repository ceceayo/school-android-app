# Idee

App waarbij:
- gebruiker notities kan maken
- notities naar vast model gemodelleerd worden
    - gekozen kan worden uit lijst
- lijst van notities
- plugin interface d.m.v. webview & javascript
- notities in formaat gebouwd bovenop markdown
    - blokken starten met H1
- geen platform-specifieke systemen gebruiken bij implementatie
    - als in: als ik dit ooit als desktop app wil maken moet het ook kunnen werken
- notities met speciale PK
    - notitie heeft i.p.v. naam b.v. datum
- metadata
    - in frontmatter
    - `dateEdited`, `dateCreated`, `formatVersion`, etc automatisch instellen 
- exporters
    - software die de notities naar bijvoorbeeld `HTML` of `LaTeX` kan exporteren
    - ook automatisch
    - geschreven in JavaScript of Python d.m.v. embedded runtime