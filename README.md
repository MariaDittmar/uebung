# Spielwiese

> Wenn du möchtest, dass alles weiterhin funktioniert,
> ändere nichts, dass mit "docker" beginnt.
> 
> Alles andere kannst du nach Belieben ändern.

## Spielwiese lokal verwenden

### Starten

```bash
docker compose up -d
```

### Stoppen

```bash
docker compose down
```

### Öffnen

http://spielwiese.test:80/

#### Windows

Windows braucht wie immer eine Extrawurst.
docker-compose.override.yml.windows muss zu docker-compose.override.yml kopiert werden.

Dort kann die Spielwiese über http://localhost:80 aufgerufen werden.

Alternative kann in der Windows `hosts`-Datei spielwiese.test auf 127.0.0.1 aufgelößt werden.