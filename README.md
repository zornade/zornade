# Siamo Zornade

[![Sponsor](https://img.shields.io/github/sponsors/zornade?style=for-the-badge&logo=github&label=Sponsor&color=ea4aaa)](https://github.com/sponsors/zornade)
[![Website](https://img.shields.io/badge/zornade.com-black?style=for-the-badge&logo=safari&logoColor=white)](https://zornade.com)
[![App](https://img.shields.io/badge/app.zornade.com-2563eb?style=for-the-badge&logo=googlemaps&logoColor=white)](https://app.zornade.com)
[![License](https://img.shields.io/badge/License-AGPL--3.0-blue?style=for-the-badge)](https://www.gnu.org/licenses/agpl-3.0.html)

> **Costruiamo l'infrastruttura aperta dei dati catastali e geospaziali italiani.**
> Codice AGPL. Dataset CC BY / ODbL. Zero tracciamento.

Il catasto italiano è un patrimonio informativo enorme — pagato dalle nostre tasse — ma accedervi è ancora complicato, lento e costoso. Lo stiamo cambiando con strumenti FOSS, API aperte e dati liberi.

---

## In numeri

| | |
|---|---|
| 🗺️ **83+ milioni** | particelle catastali italiane |
| 📍 **7.900** | comuni coperti (100% Italia) |
| 📦 **9.440** | zone CAP subcomunali (84,3% accuratezza) |
| 🔌 **2.000+** | applicazioni integrate via API |
| 📥 **2.500+** | download del dataset CAP (Sky TG24 incluso) |
| 🧪 **ETH Zurich** | validazione scientifica indipendente |
| ⏱️ **<200 ms** | latenza p50 in produzione |

---

## I nostri progetti

| Repo | Cosa fa | Stack |
|------|---------|-------|
| [**`visura-api`**](https://github.com/zornade/visura-api) ⭐ 634 | API REST per l'estrazione automatizzata di visure catastali dal portale SISTER (Agenzia delle Entrate). Playwright + SPID. | Python · FastAPI · Playwright |
| [**`zornade-parcel-downloader`**](https://github.com/zornade) | Download massivo di particelle catastali italiane con enrichment (terreno, popolazione, rischi). | Python |
| [**Plugin QGIS**](https://plugins.qgis.org/) | Integrazione nativa di Zornade in QGIS: 90+ attributi per particella, ricerca multi-modale, simbologie CORINE/sismico/subsidenza. | Python · Qt6 |
| [**`popolazione-italia-alta-risoluzione`**](https://github.com/zornade/popolazione-italia-alta-risoluzione) | Layer di popolazione ad alta risoluzione per l'Italia 2025 (~30m). Fusione dasymetric HRSL + WorldPop R2025A constrained. | Python · GDAL |

---

## zornade.com

Su [**zornade.com**](https://zornade.com) trovi:

- 🗺️ **[Mappe CAP interattive](https://app.zornade.com)** per ogni città italiana
- 🏠 **[Mappa catastale](https://app.zornade.com)** con particelle, fogli, sezioni e dati arricchiti
- 🔌 **[API catastali](https://zornade.com/api)** per sviluppatori e aziende
- 📦 **[Download gratuiti](https://zornade.com/data-downloads)** di mappe e dataset GIS
- 📰 **[Blog tecnico](https://zornade.com/blog)** e newsletter mensile

---

## La nostra filosofia

Crediamo che i dati pubblici debbano essere davvero pubblici. Per questo:

- **Tutto il codice è open source** (AGPL-3.0).
- **I dataset sono aperti** (CC BY 4.0 / ODbL).
- **Niente tracciamento, niente cookie wall, niente registrazione obbligatoria.** Una richiesta HTTP basta.
- **Attribuzione trasparente**: ogni dato mostra l'ente di origine (Agenzia delle Entrate, INGV, ISPRA, ISTAT, Ministero della Cultura, Copernicus, NASA, OpenStreetMap).
- **Niente vendor lock-in**: tutti i formati che esportiamo sono aperti (GeoJSON, GeoPackage, Shapefile, CSV).

---

## Stack

`Python` · `FastAPI` · `PostgreSQL/PostGIS` · `Supabase` · `TypeScript` · `React` · `Vite` · `Leaflet` · `Tailwind` · `Playwright` · `QGIS` · `Grafana`

---

## Supportare Zornade

Zornade è mantenuto **da una persona sola, nel tempo libero**. Se i nostri dati o strumenti ti sono utili:

- 💛 **[Sponsor su GitHub](https://github.com/sponsors/zornade)** — da $3/mese; tier per individui, professionisti, studi, enti.
- ⭐ **Metti una stella** ai repo che usi.
- 🐛 **Apri una issue** se trovi un bug o un dato sbagliato.
- 📣 **Parla di noi** a colleghi, in conferenze, sui social.
- 📝 **Scrivici un caso d'uso**: ti linkiamo volentieri.

---

## Press & menzioni

- **Sky TG24** (Aprile 2026) — analisi sui redditi IRPEF a livello sub-comunale usando il dataset Zone CAP di Zornade.
- *(Hai scritto di Zornade? [Scrivici](mailto:hello@zornade.com), aggiungiamo qui.)*

---

[**zornade.com**](https://zornade.com) · [**app.zornade.com**](https://app.zornade.com) · [**Sponsor**](https://github.com/sponsors/zornade) · [**LinkedIn**](https://linkedin.com/company/zornade)

*Dati catastali italiani, aperti e accessibili.*
