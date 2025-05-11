# Apache Log Monitoring with ELK

> Mini-projet local de pipeline de logs avec **Elasticsearch**, **Logstash** et **Kibana**, pour analyser et visualiser des fichiers `.log` au format Apache.

---

## Objectif

Mettre en place un pipeline local capable de :
- Lire des logs Apache (format `access.log`)
- Extraire les informations clés (IP, date, méthode HTTP, code réponse, etc.)
- Les stocker dans **Elasticsearch**
- Les visualiser dans **Kibana**

---

## Stack utilisée

- **Docker & Docker Compose** – orchestration des conteneurs
- **Elasticsearch** – base NoSQL orientée documents
- **Logstash** – parsing et transformation des logs
- **Kibana** – visualisation des données
- **Format de log analysé** : Apache (Combined Log Format)

---

## Lancement du projet

### 1. Cloner le repo

```bash
git clone  https://github.com/Khalilz00/log-pipeline-elk.git
cd log-pipeline-elk
```

