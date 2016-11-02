# Technische Hinweise

Das vorliegende GitBook kann einfach [geklont oder geforkt](https://github.com/iTBH/hop-on-roadmap-gitbook) werden.

## Klonen

```bash
$ git clone https://github.com/iTBH/hop-on-roadmap-gitbook.git
```

## Build

Um aus Änderungen und Ergänzungen der Dateien wieder ein neues GitBook zu bauen, ist [`gitbook-cli`](https://www.npmjs.com/package/gitbook-cli) notwendig.

Folgendes Kommando reicht aus, um das GitBook im Ordner `docs` neu zu bauen.

```bash
$ gitbook build . docs/
```

Sollte es dabei zu Fehlermeldungen kommen, müssen ggf. vorab noch die verwendeten Plugins installiert werden:

```bash
$ gitbook install
```
