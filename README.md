# degersti

Persönliche Website und technisches Notizbuch rund um **IoT, Embedded Systems, DevOps und eigene Projekte**.

Die Website basiert auf [Astro](https://astro.build/) und wird als statische Website über **GitHub Pages** veröffentlicht.

## Inhalte

Aktuell umfasst die Website unter anderem:

* **IoT Gateway** – Entwicklung eines eigenen Embedded-IoT-Gateways
* **DevOps** – Grundlagen, Notizen und praktische Beispiele zu Git, Linux, CI/CD und weiteren DevOps-Themen
* **About** – Hintergrund zur Website und zu meinen Projekten

Die Inhalte werden laufend erweitert.

## Technologien

* Astro
* HTML
* CSS
* TypeScript / JavaScript
* Markdown
* Git & GitHub
* GitHub Actions
* GitHub Pages

## Projektstruktur

```text
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Lokale Entwicklung

Repository klonen und Abhängigkeiten installieren:

```sh
npm install
```

Development-Server starten:

```sh
npm run dev
```

Die Website ist anschließend standardmäßig unter

```text
http://localhost:4321
```

erreichbar.

Für den Zugriff von anderen Geräten im lokalen Netzwerk:

```sh
npm run dev -- --host
```

## Build

Produktions-Build erstellen:

```sh
npm run build
```

Der erzeugte statische Inhalt befindet sich anschließend im Verzeichnis:

```text
dist/
```

Der Build und die Veröffentlichung über GitHub Pages erfolgen automatisiert mit **GitHub Actions**.

## Grundlage

Das Projekt wurde ursprünglich mit dem offiziellen Astro Blog Starter erstellt:

```sh
npm create astro@latest -- --template blog
```

Das ursprüngliche Theme basiert auf [Bear Blog](https://github.com/HermanMartinus/bearblog/).
