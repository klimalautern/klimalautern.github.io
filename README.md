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

## Editieren: Eigenen Fork erstellen

- Erstelle Dir einen [GitHub-Account](https://github.com/join).
- Oben auf der Website findest Du das Fork-Symbol. Damit erstellst Du einen eigenen Fork der Website.

![Fork Icon](/images/fork.png) 

- Den Fork findest Du dann bei GitHub dort, wo Du sie angelegt hast. Meiner ist hier: [https://github.com/ewolff/klimalautern.github.io](https://github.com/ewolff/klimalautern.github.io).
- Dort kannst Du nun Dateien anlegen, löschen oder editieren.
  - Es gibt im Editor ein Preview, das aber nur einen Eindruck von dem Layout gibt. Die tatsächliche Seite wird anders aussehen.

## Editieren: Eigenen Fork aktualisieren

- Da auch andere Personen an der Website arbeiten, ist es notwendig, den eigenen Fork aktuell zu halten. Dazu kann man den eigenen Fork syncen.
 
![Fork Syncen](/images/syncfork.png)

- Das sollte man immer tun, wenn der eigene Fork nicht mehr aktuell ist. GitHub meldet einem, wieviele "commit behind" der eigene Fork ist.

![Commit Behind](/images/commitbehind.png)

## Änderungen Committen: Eigenen Fork ändern

- Am Ende musst Du die Änderung jeweilt commiten. Schreibe Dazu einen aussagekrätigen Titel.
 
![Commit Nachricht](/images/commit.png).

- Mit dem Commit ist Deine eigener Fork aktualisiert, aber noch nicht die Website. Du kannst also nix kaputt machen.
- Der Commit soll direkt in den main-Branch gehen.

## Pull Request: Änderungen für die Website bereitstellen 

- Wenn soweit alles fertig ist, kannst Du einen Pull Request erstellen.
  - Mit dem Pull Request sorgst Du dafür, dass die Änderungen an Deinem eigenen Fork auf die Website kommen. Es schaut aber nochmal jemand vorher über die Änderungen. Du kannst also nix kaputt machen.

![Pull Request erstellen](/images/pullrequest.png)

- Gib dem Pull Request einen sinnvollen Namen.
- Fertig! Glückwunsch!
