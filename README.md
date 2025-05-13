# Installation et Configuration de Promtail

## Introduction
Promtail est un agent utilisé pour collecter des logs et les envoyer à Loki, un système de gestion de logs. Ce guide vous aidera à installer et configurer Promtail, en mettant l'accent sur la modification du `tenant_id`.

## Prérequis
- Clone du repository.
- Modification du tenant_id dans config/promtail.yaml (MY_TENANT).
- Modification du Loki domain dans config/promtail.yaml (MY_LOKI_DOMAIN).

## Installation

### Étape 1 : Avec Docker Compose
```bash
docker compose up -d --build --force-recreate.

