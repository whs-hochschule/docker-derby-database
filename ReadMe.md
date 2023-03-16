# Apache Derby-Datenbank mit Docker

Host eine Apache Derby-Datenbank mit Docker.

## Installation

Klone das Repository auf deinen PC und führe anschließend folgenden Befehl aus:

```shell
docker-compose up -d
```

Anschließend wird der Datenbank Container gestartet.

Die Datenbank ist nun unter `localhost:1527` erreichbar.

## Web-Oberfläche

Du kannst eine Web-Oberfläche über folgenden Link aufrufen: [http://localhost:5000](http://localhost:5000)

Anschließend kannst du neue Datenbanken erstellen und den Nutzer sowie das Passwort dafür setzen.

Es können auch Backups im ZIP-Format von den Datenbanken erstellt und wiederhergestellt werden.

Weitere Informationen findest du im entsprechendem Repository: [aditosoftware/docker-apache-derby](https://github.com/aditosoftware/docker-apache-derby)