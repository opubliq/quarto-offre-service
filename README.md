# Template Offre de Service Opubliq

Template Quarto pour créer des offres de service au style Opubliq.

## Utilisation

1. Copier `template/template.qmd` vers un nouveau dossier
2. Renommer et modifier selon les besoins
3. Générer le PDF : `quarto render mon-offre.qmd`

## Structure

```
quarto-offre-service/
├── _extensions/          # Extensions Quarto (PrettyPDF, highlight-text)
├── template/
│   └── template.qmd     # Template de base
└── exemple.qmd          # Exemple d'utilisation
```

## Sections du template

- **Abstract** : Résumé exécutif (date, client, mandat, livrables, calendrier, tarif)
- **Mandat** : Description détaillée
- **Démarche** : Méthodologie ou phases
- **Livrables** : Description des livrables
- **Calendrier** : Timeline du projet
- **Tarifs** : Investissement et modalités de paiement
