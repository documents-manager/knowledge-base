# knowledge-base

Die Projektdokumentation befindet sich im [Wiki](https://github.com/documents-manager/knowledge-base/wiki).

## Getting Started

Software Voraussetzungen:

- [docker](https://docs.docker.com/get-docker/)
- [docker-compose](https://docs.docker.com/compose/install/)

```bash
git clone https://github.com/documents-manager/knowledge-base.git
cd knowledge-base
docker-compose up
```

Die Weboberfläche ist unter [http://localhost:8080](http://localhost:8080) erreichbar.

## Limitationen

- Durch die Art und Weise wie Angular das Frontend baut, ist derzeit nur das Hosting unter `localhost` möglich. Dies soll in Zukunft konfigurierbar gestaltet werden.