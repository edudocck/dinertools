# DinerTools

Gemeinsames Repository für drei voneinander unabhängige Diner-Anwendungen:

- **Musicserver** (`musicserver/`): Musik- und Sonos-Steuerung per QR-Code.
- **POS** (`pos/`): Kassensystem (Aufnahme vorbereitet).
- **Videowall** (`videowall/`): Videowandsteuerung (Aufnahme vorbereitet).

Jede Anwendung behält ihre eigene Versionierung und Datenhaltung. Musicserver-Releases erhalten Tags im Format `music-v1.3.1`, POS-Releases `pos-v…` und Videowall-Releases `videowall-v…`. Release-Dateien müssen eindeutig dem jeweiligen Produkt zugeordnet sein. Niemals produktive `.env`-Dateien, Datenbanken oder Kennwörter committen.

Die nächste Musikserver-Erweiterung mit URL-Streams und Kategorien ist noch nicht Teil von 1.3.1.
