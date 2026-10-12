# Deployment

pilsner-vertrieb.de läuft auf dem Hetzner-Server 167.233.195.51 (klaus-server1).
Der Server holt sich alle 5 Minuten automatisch den Stand von `main`
(`/var/www/pilsner-vertrieb`, Cronjob `git pull`). Ein Push auf `main` ist damit nach spätestens 5 Minuten live.
Der frühere Server 94.130.191.178 existiert nicht mehr.
