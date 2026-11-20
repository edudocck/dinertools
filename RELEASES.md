# Unabhängige Releases

Die drei Programme teilen das Repository, nicht die Versionsnummern.

| Anwendung | Tag-Muster | ZIP-Muster |
|---|---|---|
| Musicserver | `music-v1.3.1` | `diner_musicserver_v1.3.1.zip` |
| POS | `pos-v1.0.0` | `diner_pos_v1.0.0.zip` |
| Videowall | `videowall-v1.0.0` | `diner_videowall_v1.0.0.zip` |

Zu jedem ZIP gehört ein `.zip.sha256`-Asset. Der jeweilige Updater muss **nur sein Tag-Präfix** berücksichtigen und Release-Asset, Versionsnummer und Prüfsumme verifizieren. Produktive `.env`-Dateien, SQLite-Datenbanken, Token und Backups gehören nicht ins Repository.

**Release 1.3.1 des Musikservers ist nicht bereits durch das Anlegen dieses Verzeichnisses veröffentlicht.** Ein GitHub Release mit Assets ist dafür gesondert erforderlich.
