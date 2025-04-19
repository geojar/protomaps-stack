# 🗺️ Protomaps Stack

A collection of tools and assets by [GeoJar](https://github.com/geojar) to self-host and serve vector basemaps using [Protomaps](https://protomaps.com/) and [MapLibre GL JS](https://maplibre.org/).

This stack allows for downloading, serving, and visualizing vector tiles with a lightweight, fully self-hosted setup.

---

## 📦 Repositories

### [`protomaps-assets-basemaps`](https://github.com/geojar/protomaps-assets-basemaps)
Clones the official [Protomaps basemaps](https://github.com/protomaps/basemaps) into a GeoJar-managed repository. These assets can be customized and are intended to be published for use with MapLibre GL JS.

### [`protomaps-assets-maplibre`](https://github.com/geojar/protomaps-assets-maplibre)
Includes the necessary frontend assets to render a map using MapLibre:
- HTML map viewer
- CSS & JavaScript
- JSON configuration files for style and sources

This is the public-facing map viewer component.

### [`protomaps-tileserver-docker`](https://github.com/geojar/protomaps-tileserver-docker)
Dockerized Protomaps tileserver setup. This includes:
- A tile server capable of serving PMTiles
- A download helper script to fetch vector tiles from Protomaps
  - Download the full world
  - Or extract tiles by bounding box

---

## 🌐 Use Case

This stack is ideal for:
- Hosting custom basemaps without relying on third-party tile servers
- Offline or edge deployments
- Full control over style, tiles, and performance

---

## 🚀 Getting Started

Check out each repository's README for setup instructions:

- **[Basemaps](https://github.com/geojar/protomaps-assets-basemaps)** – Get the tiles and styles
- **[MapLibre Assets](https://github.com/geojar/protomaps-assets-maplibre)** – Build and serve the frontend
- **[Tileserver Docker](https://github.com/geojar/protomaps-tileserver-docker)** – Spin up your tile server

---

### 🤖 AI-Assisted Content

Some parts of this project, especially the README and other documentation, were created or refined with the help of AI tools (such as ChatGPT). These tools were used to improve clarity, structure, and consistency in presenting the information. All generated content was reviewed and edited as needed to ensure accuracy and alignment with the project’s goals.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.