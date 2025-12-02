# Template Offre de Service Opubliq

Template Quarto pour créer des offres de service au style Opubliq.

## Utilisation

```bash
quarto use template opubliq/quarto-offre-service
```

Puis renommer `template.qmd` et modifier selon les besoins.

Générer le PDF :
```bash
quarto render mon-offre.qmd
```

## Structure

```
├── _extensions/
│   └── opubliq-offre-service/   # Extension custom Opubliq
├── _quarto.yml                  # Configuration
└── template.qmd                 # Template de base
```

## Sections du template

- **Abstract** : Résumé exécutif (date, client, mandat, livrables, calendrier, tarif)
- **Mandat** : Description détaillée
- **Démarche** : Méthodologie ou phases
- **Livrables** : Description des livrables
- **Calendrier** : Timeline du projet
- **Tarifs** : Investissement et modalités de paiement
