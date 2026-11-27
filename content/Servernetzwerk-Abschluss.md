# Servernetzwerk – Abschluss

Das Umsetzungspaket für das lokale Servernetzwerk ist erstellt und unter [archive/server_network](./archive/server_network/README.md) archiviert.

Enthalten sind Rollout-Skripte für den Server-Access-Point auf hokage sowie IPv4-Forwarding und NAT auf kakashi.dev. Die Skripte verwenden die dokumentierten Interfaces, sichern bestehende Konfigurationen und speichern keine WLAN-Zugangsdaten im Repository.

Die Installation wurde nicht auf den Geräten ausgeführt. Vor dem produktiven Einsatz auf beiden Hosts `--check` und anschließend bewusst `--apply` ausführen; WLAN, DNS, Dienste, Internetweiterleitung und Neustartverhalten danach vor Ort prüfen.
