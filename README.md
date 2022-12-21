# Webpage KlimaLautern

Dies ist der Quellcode für die Webseite von [KlimaLautern](https://klimalautern.de/). Es ist eine GitHub Page.

Mehr Infos zu  [GitHub Pages](https://docs.github.com/de/pages/getting-started-with-github-pages/about-github-pages).

Die Seiten sind in [Markdown](https://github.github.com/gfm/) geschrieben.

## Blog / Veranstaltungen.

Im Unterverzeichnis _posts kann man neue Blog-Beiträge hinterlegen.

Die Einträge sollten mit solchen Einträgen beginnen:
```
---
title: Unser Erstes Arbeitstreffen
layout: post
description: Die inhaltliche Arbeit beginnt mit dem ersten Arbeitstreffen
thumbnail: /images/2022-12-01-erstes-arbeitstreffen.jpg
tags: Veranstaltung
---
Hier steht Markdown-Text.
```

- Das Thumbnail wird auch beim Überblick genutzt.
- Bei den Tags gibt es im Moment nur Veranstaltungen, später können wir noch andere Tags einfügen.
- Darunter steht dann der Text als [Markdown](https://github.github.com/gfm/).

## Editieren

- Erstelle Dir einen [GitHub-Account](https://github.com/join).
- Oben auf der Website findest Du das Fork-Symbol. Damit erstellst Du eine eigene Kopie der Website. ![Fork Icon](/images/fork.png) 
- Die Kopie findest Du dann bei GitHub dort, wo Du sie angelegt hast. Meine ist hier: [https://github.com/ewolff/klimalautern.github.io](https://github.com/ewolff/klimalautern.github.io).
- Dort kannst Du nun Dateien anlegen, löschen oder editieren.
  - Es gibt ein Preview, das aber nur einen Eindruck von dem Layout gibt. Die tatsächliche Seite wird anders aussehen.
- Am Ende musst Du die Änderung jeweilt commiten. Schreibe Dazu einen aussagekrätigen Titel. Hier ist ein Beispiel: ![Commit Nachricht](/images/commit.png).
  - Der Commit soll direkt in den main-Branch gehen.
  - Mit dem Commit ist Deine eigene Kopie aktualisiert, aber noch nicht die Website. Du kannst also nix kaputt machen.
- Wenn soweit alles fertig ist, kannst Du einen Pull Request erstellen.
