# Statut de Prowess

Sondes externes de Prowess, avec [Upptime](https://github.com/upptime/upptime) : toutes les 5 minutes depuis GitHub Actions, hors de l'hébergement Scaleway. Une panne ouvre une issue, fermée au retour du service.

<!--live status--> **🟩 All systems operational**

<!--start: status pages-->
<!--end: status pages-->

## Fonctionnement

- `Uptime CI` sonde les adresses de `.upptimerc.yml` ; `Response Time CI`, `Summary CI` et `Graphs CI` tiennent l'historique et ce résumé.
- Jeton intégré de GitHub Actions seulement, permissions déclarées dans chaque workflow, actions figées par SHA.
- Pas de mise à jour automatique du modèle Upptime (workflows `update-template` et `updates` retirés) : une nouvelle version se reporte à la main, SHA compris.
- Pas de page de statut publique pour l'instant.
