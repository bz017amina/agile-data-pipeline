# Agile Data Pipeline

## Description

Ce projet présente la mise en œuvre d'un pipeline DataOps structuré pour le traitement de données de ventes.

Le pipeline comprend :

- Ingestion des données CSV
- Stockage dans DuckDB
- Validation des données
- Transformation avec dbt
- Tests de qualité des données
- Orchestration avec Dagster
- Versionnement avec Git
- Intégration continue avec GitHub Actions

## Architecture du Pipeline

ventes.csv
↓
Ingestion
↓
DuckDB
↓
Validation
↓
dbt Transformation
↓
dbt Tests
↓
Dagster
↓
CI GitHub Actions

## Technologies utilisées

- Python
- DuckDB
- dbt
- Dagster
- Git
- GitHub Actions

## Structure du projet

```text
data/
pipeline/
dbt_pipeline/
.github/
docs/
```

## Auteur

Amina BOUAZZA

Master Intelligence Artificielle