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
Wird das Backend nicht auf `localhost:8081` deployed, muss die entsprechende Domain und der Port in `knowledge-base/config/prod.json` eingetragen werden.  
Dafür ist der `config` Ordner als Volume des documentdoor services in der `docker-compose.yml` unter `/usr/share/nginx/html/config` eingehangen.
