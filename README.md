# 🎼 Greycin Kim — Data Engineering for Music & Audio Systems

I design ETL pipelines, data warehouses, and analytics platforms using MIDI, MusicXML, and audio metadata as real-world datasets.

*No hymns. No choir. Just music data.*

---

## 1️⃣ MIDI → Data Warehouse ETL Pipeline

**Repo:** `midi-etl-data-warehouse`  
**Stack:** Python, Music21, Prefect/Airflow, PostgreSQL/BigQuery

### Pipeline:
- **Extract** thousands of MIDI files (jazz, classical, pop, game music)
- **Transform** into structured features:
  - key
  - tempo
  - note density
  - chord movement
  - track/instrument separation
- **Load** into warehouse

*This is a textbook ETL system using non-traditional data.*

---

## 2️⃣ SATB / Multi-Track Voice Data Modeler (now generalized)

**Repo:** `multitrack-music-dataset-builder`  
**Stack:** Python, MusicXML, PostgreSQL

Parse multi-track scores into tables:

| piece_id | track | pitch | duration | measure | instrument |
|----------|-------|-------|----------|---------|------------|

*Pure data modeling from complex structured files.*

---

## 3️⃣ Music Analytics BI Dashboard

**Repo:** `music-bi-dashboard`  
**Stack:** Power BI / Tableau

Dashboards from your warehouse:
- Key distributions
- Tempo patterns
- Track complexity
- Instrument density
- Song difficulty score

*Shows real BI on top of engineered data.*

---

## 4️⃣ Real-Time Music Transposition API (Data Service)

**Repo:** `music-transpose-api`  
**Stack:** Flask, Redis, PostgreSQL

API that pulls music data from DB, transforms it, returns new version.

*This shows data services, not just analysis.*

---

## 5️⃣ Spotify Audio Features Ingestion Pipeline

**Repo:** `spotify-audio-metadata-pipeline`  
**Stack:** Spotify API → Python → BigQuery → BI

Daily ingestion job with freshness.

---

## 🧾 What These Projects Demonstrate

- ETL / ELT pipeline design
- Data modeling from complex file formats
- Warehouse + BI analytics
- Data APIs and microservices
- Workflow orchestration
