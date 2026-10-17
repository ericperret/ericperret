# Eric PERRET

🇫🇷 [Version française](LISEZMOI.md)

**Engineer first, language second.**

I design algorithms and simulations. Then I choose the right tool.  
For universal deployment — PC, tablet, smartphone — the browser is the runtime.

![Algorithms](https://img.shields.io/badge/Algorithms-Engineering-blue?style=for-the-badge)
![Embedded](https://img.shields.io/badge/Embedded-ESP32-E7352C?style=for-the-badge)
![GIS](https://img.shields.io/badge/GIS-Geospatial-2E8B57?style=for-the-badge)
![Simulation](https://img.shields.io/badge/Simulation-Scientific-orange?style=for-the-badge)
![Browser](https://img.shields.io/badge/Browser-First-1E90FF?style=for-the-badge)
![Zero deps](https://img.shields.io/badge/Zero-Dependencies-black?style=for-the-badge)

Zero dependencies. Runs everywhere. Every browser project below opens with one click (▶️).

---

### 🚗 OBD CAR - CAN Bridge

Standalone OBD-II diagnostic bridge for ESP32-S3, zero external libraries. MCP2515 driven via raw SPI register access. ISO 15765-4 29-bit, functional (broadcast) addressing. Live Mode 01 PID discovery and decoding, DTC read/clear (Mode 03/07/0A/04), driving data logger with power-loss detection, WiFi web interface with real-time gauges.  
**Validated** on a real Citroën Nemo 1.3 HDi (Marelli MJD 8F3.F6).

[![OBD](https://img.shields.io/badge/OBD-CAN_Bridge-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/obd)
![ESP32-S3](https://img.shields.io/badge/ESP32--S3-XIAO-4fc3f7?style=flat-square)
![OBD-II](https://img.shields.io/badge/OBD--II-ISO15765--4-ffa726?style=flat-square)
![CAN](https://img.shields.io/badge/CAN-11_|_29_bit-26c6da?style=flat-square)
![WiFi](https://img.shields.io/badge/WiFi-Web_Interface-66bb6a?style=flat-square)
![Zero deps](https://img.shields.io/badge/Zero-dependencies-ef5350?style=flat-square)

### 🚁 DroneRX V3.4

**Multi-protocol drone detection & identification** on M5Stack CoreS3 (ESP32-S3).

Passive WiFi sniffer detecting **4 protocols** (FR SGDSN, ODID ASTM F3411, DJI, Parrot) + beacon TX (FR + ODID).  
Self-contained HTML interface with real-time map, **ADS-B** aircraft overlay, **60s trajectory prediction** with collision cone, weather, and TX remote configuration.

[![DroneRX](https://img.shields.io/badge/DroneRX-V3.4-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/DroneRX)
![ESP32](https://img.shields.io/badge/ESP32--S3-M5Stack_CoreS3-66bb6a?style=flat-square)
![Protocols](https://img.shields.io/badge/Protocols-FR_|_ODID_|_DJI_|_Parrot-ffa726?style=flat-square)
![ADS-B](https://img.shields.io/badge/ADS--B-OpenSky-26c6da?style=flat-square)

---

### 🏔️ CREST — Relief, Glaciers & Dam Break Simulation

**Browser-based 3D terrain viewer and multi-physics simulator.** Zero server, zero installation, pure HTML/JS.

Client-side processing of Copernicus GLO-30 DEMs. Features a complete paleo-glacier simulation (-30ka to today) with orbital forcing and ice flow (SIA). Includes a 2D Saint-Venant hydrodynamic solver for dam break simulations, **validated against the 1959 Malpasset historical disaster**. Fully parallelized via Web Workers.

[![Launch](https://img.shields.io/badge/▶_Launch-CREST-66bb6a?style=for-the-badge)](https://ericperret.github.io/crest/map.html)
[![CREST](https://img.shields.io/badge/CREST-Repository-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/crest)
![Physics](https://img.shields.io/badge/Physics-Saint--Venant_|_SIA-ffa726?style=flat-square)
![Web Workers](https://img.shields.io/badge/Web-Workers-26c6da?style=flat-square)
![Zero deps](https://img.shields.io/badge/Zero-dependencies-ef5350?style=flat-square)

---

### 🗺️ DXF-PCI Inspector — French Cadastre Viewer

**Single-file HTML viewer and field tool for the French cadastral plan (DGFiP PCI, DXF format).** Zero server, zero installation, works offline. Built for land surveyors and land services, ready for emergency and intervention services.

Reads a whole department delivery in the browser, `.tar.bz2` archives decompressed client-side, 34,969 French communes embedded. Parcels and buildings coloured by occupancy, full XDATA record on hover, parcel search by IDU. Street and locality index per commune: click a street to frame it end to end, click a house number to centre on it. Neighbouring sheets on double-click, merged sheets on Ctrl+click, department overview map and commune mini-map. Snapping area and polyline measurement, assisted parcel division at a given area, exports to surveyor DA files, scaled PNG and GeoJSON for QGIS. Inventory checked against the DXF-PCI standard.  
**Personal project** (own time), inspired by professional land-management work, tested on the French Guiana (973) delivery.

[![Launch](https://img.shields.io/badge/▶_Launch-DXF--PCI_Inspector-66bb6a?style=for-the-badge)](https://ericperret.github.io/cadastre/cadastre_dxf_inspecteur_v21.html)
[![DXF-PCI](https://img.shields.io/badge/DXF--PCI-Repository-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/cadastre)
![Cadastre](https://img.shields.io/badge/Cadastre-DGFiP_PCI-66bb6a?style=flat-square)
![Projections](https://img.shields.io/badge/CRS-UTM_22N_|_Lambert--93-ffa726?style=flat-square)
![Offline](https://img.shields.io/badge/Offline-Browser_only-26c6da?style=flat-square)
![Zero deps](https://img.shields.io/badge/Zero-dependencies-ef5350?style=flat-square)

---

### 🗄️ SQL Studio

**SQL Learning tool — embedded full SQL interpreter, embedded DB, all in one HTML file.** No server. No dependencies. No install.

SELECT · INNER JOIN · LEFT JOIN · CASE WHEN · BETWEEN · INSERT · UPDATE · CREATE TABLE · DISTINCT · ORDER BY · LIMIT · spatial ST_* functions  
**Training mode** — 15 progressive exercises across 10 levels. Validated on output, not syntax.  
Import/export CSV. localStorage persistence. Academic course bubbles per level.

[![Launch](https://img.shields.io/badge/▶_Launch-SQL_Studio-66bb6a?style=for-the-badge)](https://ericperret.github.io/sql_studio/sql_studio.html)
[![SQL Studio](https://img.shields.io/badge/SQL_Studio-Repository-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/sql_studio)
![SQL](https://img.shields.io/badge/SQL-interpreter-4fc3f7?style=flat-square)
![Training](https://img.shields.io/badge/Training-15_exercises-ffa726?style=flat-square)
![Zero deps](https://img.shields.io/badge/Zero-dependencies-ef5350?style=flat-square)

---

### 🎯 Khéops v4.3 — Acoustic drone localisation

**Browser simulator of acoustic drone direction finding by TDOA** on a 5-microphone pyramid: 1 MHz ADC chain with GCC-PHAT correlation, sliding least-squares trajectory, identification camera with timers, live weather, and a study tab to size the pyramid (time to focus at 1° vs. base size). Bilingual interface (browser language).

[![Launch](https://img.shields.io/badge/▶_Launch-Khéops_v4.3-66bb6a?style=for-the-badge)](https://ericperret.github.io/One-Page-One-Mission/kheops_v43.html)
[![Khéops](https://img.shields.io/badge/Khéops-Repository-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/One-Page-One-Mission)
![TDOA](https://img.shields.io/badge/TDOA-GCC--PHAT-ffa726?style=flat-square)
![Zero deps](https://img.shields.io/badge/Zero-dependencies-ef5350?style=flat-square)

---

### 🚀 APPELS AUX TESTEURS (Besoin de 20 testeurs)

Je cherche des testeurs pour valider mes applications sur le Play Store.

1. **Rejoindre le groupe :** [Groupe Google azsfr](https://groups.google.com/g/azsfr)

2. **Retour :** Je teste votre app en retour ! Contactez-moi par email ou via une Issue.

---

### What I build

**Geosciences & Simulation** — Paleo-glacier modeling, 2D hydrodynamic dam breaks (Saint-Venant), Copernicus DEM processing, ballistic and gas dispersion  
**GIS & Cadastre** — DXF-PCI cadastral viewer, street and house-number indexing, parcel division, surveyor exports  
**Drone Detection & Identification** — Multi-protocol WiFi sniffer, ODID beacon TX, ADS-B integration, trajectory prediction, acoustic TDOA localisation  
**Signal Processing** — Acoustic localization, TDOA, GCC-PHAT, DVB-S transmission chains, SSTV, antennas  
**Cryptanalysis** — Classical cipher breaking, n-gram scoring, simulated annealing, Kryptos / Zodiac  
**Structural Engineering** — Seismic base isolation, price / risk optimisation, device installation plan  
**Healthcare Tools** — Paediatric triage (approved by emergency physicians), self-orientation questionnaire, music therapy  
**Education** — SQL learning tool, drone & aviation exam training, primary-school maths and reading tools

### Live Demos

| Project | Launch | Description |
|---------|--------|-------------|
| [**obd**](https://github.com/ericperret/obd) | — | 🚗 OBD-II CAN bridge — diagnostics, CAN sniffing & web interface — ESP32-S3 |
| [**DroneRX**](https://github.com/ericperret/DroneRX) | — | 🚁 Multi-protocol drone detection — FR/ODID/DJI/Parrot — ESP32-S3 + ADS-B |
| [**quizz**](https://github.com/ericperret/quizz) | [▶️ all tools](https://ericperret.github.io/quizz/index2.html) | 🎓 Drone & aviation exams, school tools, ⭐ paediatric triage, games |
| [**CREST**](https://github.com/ericperret/crest) | [▶️ map](https://ericperret.github.io/crest/map.html) | 🏔️ 3D DEM viewer, paleo-glacier & dam break simulator (Saint-Venant 2D, Malpasset validated) |
| [**Sismic**](https://github.com/ericperret/Sismic) | [▶️ simulator](https://ericperret.github.io/Sismic/simulateur_sismique.html) | 🏠 Seismic isolation of a house — price / risk curve and installation plan of the devices (pendulums, dampers, stops), 21 earthquakes |
| [**dispersion**](https://github.com/ericperret/dispersion) | [▶️ v6.2](https://ericperret.github.io/dispersion/dispersion_v62.html) | 🚀 Ballistic & gas dispersion (CSG/Kourou and world launch pads) — RK45, Pasquill-Gifford, live wind |
| [**cadastre**](https://github.com/ericperret/cadastre) | [▶️ inspector](https://ericperret.github.io/cadastre/cadastre_dxf_inspecteur_v21.html) | 🗺️ French cadastre DXF-PCI viewer — streets & house numbers, parcel division, DA / GeoJSON export |
| [**JPEG2DVB**](https://github.com/ericperret/JPEG2DVB) | [▶️ 15 steps](https://ericperret.github.io/JPEG2DVB/index2.html) | 📡 DVB-S transmission chain step by step — DCT to QPSK and SRRC |
| [**code**](https://github.com/ericperret/code) | [▶️ cracker](https://ericperret.github.io/code/multi_cipher_v3_24_0.html) · [▶️ battleship](https://ericperret.github.io/code/bataille_navale_v6.html) | 🔐 Multi-Cipher Cracker v3.24 (30+ classical ciphers) · cryptographic battleship |
| [**sql_studio**](https://github.com/ericperret/sql_studio) | [▶️ SQL Studio](https://ericperret.github.io/sql_studio/sql_studio.html) | 🗄️ SQL learning tool — embedded interpreter + DB |
| [**One-Page-One-Mission**](https://github.com/ericperret/One-Page-One-Mission) | [▶️ Khéops](https://ericperret.github.io/One-Page-One-Mission/kheops_v43.html) | 🎯 Acoustic drone localisation — TDOA, 5-mic pyramid, GCC-PHAT, camera tracking |
| [**sstv**](https://github.com/ericperret/sstv) | [▶️ tools](https://ericperret.github.io/sstv/index2.html) | 📻 Slow Scan TV — WAV encoder, decoder (file & live), diagnostic |
| [**lpda**](https://github.com/ericperret/lpda) | [▶️ calculator](https://ericperret.github.io/lpda/lpda_uhf.html) | 📶 UHF log-periodic antenna — cut lengths, optimum angle, drilling plan |
| [**photo**](https://github.com/ericperret/photo) | [▶️ perspective](https://ericperret.github.io/photo/perspective-correction-filtres.html) | 📸 Six image & geodata tools — perspective, YUV levels, JPEG forensic, GeoTIFF, DEM tiles |

---

### Philosophy
Analysis → Design → Algorithm → Then choose the language.
Not the other way around.

Portable. Autonomous. No framework. No build step.  
Open the file. It works.

---

### Background

**2023 – Now** — Ministère de l'Intérieur · Technicien SIC CS 'Administrateur SIG'  
**2018 – 2022** — Ministère de l'Intérieur · Technicien SIC CN 'Multimedia'  
**2003 – 2016** — AZS (founder) · Electronics for defense & security  
**1998 – 2003** — SOFIM · UNIX Engineer, high availability (HACMP)  
**1996 – 1997** — Thaï Radiators · ISO 9001, test lab setup  
**1994 – 1996** — IBM · Cleanroom production, ion implantation  
**1993** — Service National Sécurité civile  
**1992** — ESI Sup'info · Analyst Programmer  
**1989** — Medicine entrance exam (Nancy) · Admitted  
**1988** — Baccalauréat C · Nancy-Metz

---

### Certifications & Licenses

📻 Ham radio F1OCM since 1986 now FY4AY  
✈️ Private pilot training  
⛵ Coastal boat license  
🤿 Scuba diving level 1  
⚡ Electrical certification BR-B2V  
🏗️ CACES R386 1B, 3B (PEMP)  
🚁 Drone CATS & BAPD (A1/A3 + A2)  
🚑 First aid & fire safety

---

<sub>French Guiana 🇬🇫 </sub>
