# Zornade

[![Sponsor](https://img.shields.io/github/sponsors/zornade?style=for-the-badge&logo=github&label=Sponsor&color=ea4aaa)](https://github.com/sponsors/zornade)
[![Website](https://img.shields.io/badge/zornade.com-black?style=for-the-badge&logo=safari&logoColor=white)](https://zornade.com)
[![App](https://img.shields.io/badge/app.zornade.com-2563eb?style=for-the-badge&logo=googlemaps&logoColor=white)](https://app.zornade.com)
[![Licenza](https://img.shields.io/badge/Codice-AGPL--3.0%20%2F%20MIT%20%2F%20GPL--2.0-blue?style=for-the-badge)](https://github.com/zornade/visura-api/blob/main/LICENSE)

Siamo una software house di Trieste. Mettiamo insieme i dati territoriali
italiani in un formato che si può interrogare: **88 milioni di particelle**
catastali, **19 blocchi di dati** da **oltre 15 fonti ufficiali**, un profilo per
particella.

## Cosa togliamo di mezzo

Il catasto è pubblico. Per leggerlo servono SPID, una convenzione con l'Agenzia
delle Entrate e un browser. Le quotazioni OMI stanno su un altro portale, il
rischio idrogeologico su un terzo, la subsidenza satellitare su un quarto. Chi
deve decidere su un immobile apre sei sistemi e ricopia a mano.

Quel lavoro lo facciamo una volta, su tutte le particelle, e lo mettiamo in un
posto solo. Ci si arriva da un'API REST, da una mappa, da un plugin QGIS, da un
dataset GeoPackage o da un assistente AI che parla il protocollo MCP.

## Perché i dati sono gratis e il codice è pubblico

**I dati sono già di tutti.** Il piano gratuito non scade: piattaforma, dataset e
API a 10.000 richieste all'ora, con cinque token per utente. Consultare e
analizzare non costa nulla.

**La provenienza si controlla.** Ogni valore porta la sua fonte e la sua licenza,
blocco per blocco, e il codice dei client è pubblico: chi vuole rifare il calcolo
può leggere come è fatto, o rifarlo.

**Chi paga non è chi consulta.** A pagare è chi integra il dato dentro un
prodotto, non il geometra che apre una mappa per guardare un foglio.

## Come guadagniamo

Nessuna di queste voci toglie qualcosa al piano gratuito.

| Voce | Prezzo | Per chi |
|------|--------|---------|
| Piattaforma, dataset e API | 0 € | chi consulta e analizza |
| [Licenza commerciale](https://zornade.com/licenza-commerciale) | da 490 € / anno | chi integra il dato in un prodotto e non vuole l'attribuzione Zornade |
| [Supporto e continuità](https://zornade.com/continuita) | da 1.800 € / anno | chi ha bisogno di tempi di risposta scritti e di un referente |
| [Estratto dati su misura](https://zornade.com/estrazioni-dati-catastali) | da 3.900 € | chi vuole le particelle di una provincia o dell'Italia intera |
| [Su misura](https://zornade.com/servizi-sviluppo-software) | a preventivo | white label, on-premise, sviluppo su specifica |

La voce più grande del fatturato resta l'ultima. Scriviamo software per aziende
che hanno già un prodotto e devono aggiungerci il dato catastale, per chi
rivende la nostra API con il proprio marchio, e per chi ha bisogno di un backend
geografico che regga il traffico.

## Progetti

| Progetto | Cosa fa | Licenza |
|----------|---------|---------|
| [visura-api](https://github.com/zornade/visura-api) | estrae visure dal portale SISTER con le proprie credenziali, dietro un'API REST | AGPL-3.0 |
| [zornade-mcp](https://github.com/zornade/zornade-mcp) | server MCP con sei strumenti di sola lettura per ChatGPT, Claude, Cursor e VS Code | MIT |
| [zornade-parcel-downloader](https://github.com/zornade/zornade-parcel-downloader) | plugin QGIS che scarica particelle arricchite con rischio, OMI e uso del suolo | GPL-2.0 |
| [zornade-studio](https://github.com/zornade/zornade-studio) | editor per costruire mappe e grafici sui nostri geodati | AGPL-3.0 |

## Numeri

Misurati il 2 novembre 2026.

- 88.709.614 particelle catastali
- 19 blocchi di dati, da oltre 15 fonti ufficiali (Agenzia delle Entrate, ISTAT, INGV, ISPRA, MEF, Copernicus, NASA, JRC, MiC, OpenStreetMap)
- 18,7 milioni di indirizzi ANNCSU per il geocoding
- 13 dataset aperti, scaricabili senza registrazione, con la licenza dichiarata uno per uno

## Sponsor

Chi usa i dati per lavoro e vuole che restino aggiornati può sostenerli in due
modi.

- Persone: [github.com/sponsors/zornade](https://github.com/sponsors/zornade)
- Aziende: [zornade.com/sponsor](https://zornade.com/sponsor), tre livelli da 900, 2.400 e 4.900 euro l'anno

Le regole del programma sono scritte in chiaro: nessun link comprato, i link
commerciali escono con `rel="sponsored"`, l'etichetta di sponsor resta visibile e
c'è un'azienda per categoria merceologica.

## Dove

- Sito e documentazione: [zornade.com](https://zornade.com)
- App, mappe e documenti: [app.zornade.com](https://app.zornade.com)
- Specifica OpenAPI: [api.zornade.com/api/v2/openapi.json](https://api.zornade.com/api/v2/openapi.json)
- Dataset aperti: [zornade.com/data-downloads](https://zornade.com/data-downloads)
- Mappe e grafici: [studio.zornade.com](https://studio.zornade.com)
- Server MCP: `https://mcp.zornade.com/mcp`
- Newsletter: [newsletter.zornade.com](https://newsletter.zornade.com)

Per scriverci: hello@zornade.com
