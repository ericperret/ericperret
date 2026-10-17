# Eric PERRET

🇬🇧 [English version](README.md)

**L'ingénierie d'abord, le langage ensuite.**

Je conçois des algorithmes et des simulations, puis je choisis le bon outil.  
Pour un déploiement universel — PC, tablette, smartphone — le navigateur est l'environnement d'exécution.

![Algorithmes](https://img.shields.io/badge/Algorithmes-Ingénierie-blue?style=for-the-badge)
![Embarqué](https://img.shields.io/badge/Embarqué-ESP32-E7352C?style=for-the-badge)
![SIG](https://img.shields.io/badge/SIG-Géospatial-2E8B57?style=for-the-badge)
![Simulation](https://img.shields.io/badge/Simulation-Scientifique-orange?style=for-the-badge)
![Navigateur](https://img.shields.io/badge/Navigateur-d'abord-1E90FF?style=for-the-badge)
![Zéro dépendance](https://img.shields.io/badge/Zéro-dépendance-black?style=for-the-badge)

Zéro dépendance. Fonctionne partout. Chaque projet navigateur ci-dessous s'ouvre en un clic (▶️).

---

### 🚗 OBD CAR - Passerelle CAN

Passerelle de diagnostic OBD-II autonome pour ESP32-S3, sans aucune librairie externe. MCP2515 piloté par accès direct aux registres SPI. ISO 15765-4 29 bits, adressage fonctionnel (diffusion). Découverte et décodage des PID en direct (mode 01), lecture et effacement des codes défaut (modes 03/07/0A/04), enregistreur de conduite avec détection de coupure d'alimentation, interface web WiFi avec jauges en temps réel.  
**Validé** sur un vrai Citroën Nemo 1.3 HDi (Marelli MJD 8F3.F6).

[![OBD](https://img.shields.io/badge/OBD-Passerelle_CAN-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/obd)
![ESP32-S3](https://img.shields.io/badge/ESP32--S3-XIAO-4fc3f7?style=flat-square)
![OBD-II](https://img.shields.io/badge/OBD--II-ISO15765--4-ffa726?style=flat-square)
![CAN](https://img.shields.io/badge/CAN-11_|_29_bits-26c6da?style=flat-square)
![WiFi](https://img.shields.io/badge/WiFi-Interface_web-66bb6a?style=flat-square)
![Zéro dépendance](https://img.shields.io/badge/Zéro-dépendance-ef5350?style=flat-square)

### 🚁 DroneRX V3.4

**Détection et identification de drones multi-protocole** sur M5Stack CoreS3 (ESP32-S3).

Écoute WiFi passive détectant **4 protocoles** (FR SGDSN, ODID ASTM F3411, DJI, Parrot) + émission de balise (FR + ODID).  
Interface HTML autonome avec carte en temps réel, superposition des aéronefs **ADS-B**, **prédiction de trajectoire à 60 s** avec cône de collision, météo et configuration à distance de l'émetteur.

[![DroneRX](https://img.shields.io/badge/DroneRX-V3.4-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/DroneRX)
![ESP32](https://img.shields.io/badge/ESP32--S3-M5Stack_CoreS3-66bb6a?style=flat-square)
![Protocoles](https://img.shields.io/badge/Protocoles-FR_|_ODID_|_DJI_|_Parrot-ffa726?style=flat-square)
![ADS-B](https://img.shields.io/badge/ADS--B-OpenSky-26c6da?style=flat-square)

---

### 🏔️ CREST — Relief, glaciers et rupture de barrage

**Visualiseur de relief 3D et simulateur multiphysique dans le navigateur.** Aucun serveur, aucune installation, HTML/JS pur.

Traitement côté client des MNT Copernicus GLO-30. Simulation complète de paléoglaciers (−30 ka à aujourd'hui) avec forçage orbital et écoulement de la glace (SIA). Solveur hydrodynamique de Saint-Venant 2D pour les ruptures de barrage, **validé sur la catastrophe historique de Malpasset (1959)**. Entièrement parallélisé par Web Workers.

[![Lancer](https://img.shields.io/badge/▶_Lancer-CREST-66bb6a?style=for-the-badge)](https://ericperret.github.io/crest/map.html)
[![CREST](https://img.shields.io/badge/CREST-Dépôt-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/crest)
![Physique](https://img.shields.io/badge/Physique-Saint--Venant_|_SIA-ffa726?style=flat-square)
![Web Workers](https://img.shields.io/badge/Web-Workers-26c6da?style=flat-square)
![Zéro dépendance](https://img.shields.io/badge/Zéro-dépendance-ef5350?style=flat-square)

---

### 🗺️ Inspecteur DXF-PCI — Visionneuse du cadastre

**Visionneuse et outil de terrain en un seul fichier HTML pour le Plan Cadastral Informatisé (DGFiP PCI, format DXF).** Aucun serveur, aucune installation, fonctionne hors ligne. Conçu pour les géomètres et les services fonciers, prêt pour les services d'urgence et d'intervention.

Lit une livraison départementale entière dans le navigateur, archives `.tar.bz2` décompressées sur le poste, 34 969 communes françaises intégrées. Parcelles et bâtiments colorés selon l'occupation, fiche XDATA complète au survol, recherche de parcelle par IDU. Index des rues et lieux-dits par commune : clic sur une rue pour la cadrer de bout en bout, clic sur un numéro pour centrer la vue. Planches voisines au double-clic, planches fusionnées au Ctrl+clic, carte de synthèse du département et mini-carte de la commune. Mesure de surface et de polyligne magnétique, division assistée d'une parcelle à contenance donnée, exports DA géomètre, PNG à l'échelle et GeoJSON pour QGIS. Inventaire confronté à la norme DXF-PCI.  
**Projet personnel** (sur temps personnel), inspiré du travail professionnel en gestion du foncier, testé sur la livraison de la Guyane (973).

[![Lancer](https://img.shields.io/badge/▶_Lancer-Inspecteur_DXF--PCI-66bb6a?style=for-the-badge)](https://ericperret.github.io/cadastre/cadastre_dxf_inspecteur_v21.html)
[![DXF-PCI](https://img.shields.io/badge/DXF--PCI-Dépôt-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/cadastre)
![Cadastre](https://img.shields.io/badge/Cadastre-DGFiP_PCI-66bb6a?style=flat-square)
![Projections](https://img.shields.io/badge/Projection-UTM_22N_|_Lambert--93-ffa726?style=flat-square)
![Hors ligne](https://img.shields.io/badge/Hors_ligne-Navigateur_seul-26c6da?style=flat-square)
![Zéro dépendance](https://img.shields.io/badge/Zéro-dépendance-ef5350?style=flat-square)

---

### 🗄️ SQL Studio

**Outil d'apprentissage du SQL — interpréteur SQL complet et base de données intégrés, le tout dans un seul fichier HTML.** Aucun serveur. Aucune dépendance. Aucune installation.

SELECT · INNER JOIN · LEFT JOIN · CASE WHEN · BETWEEN · INSERT · UPDATE · CREATE TABLE · DISTINCT · ORDER BY · LIMIT · fonctions spatiales ST_*  
**Mode Training** — 15 exercices progressifs sur 10 niveaux. Validation sur le résultat, pas sur la syntaxe.  
Import / export CSV. Sauvegarde en localStorage. Bulles de cours par niveau.

[![Lancer](https://img.shields.io/badge/▶_Lancer-SQL_Studio-66bb6a?style=for-the-badge)](https://ericperret.github.io/sql_studio/sql_studio.html)
[![SQL Studio](https://img.shields.io/badge/SQL_Studio-Dépôt-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/sql_studio)
![SQL](https://img.shields.io/badge/SQL-interpréteur-4fc3f7?style=flat-square)
![Training](https://img.shields.io/badge/Training-15_exercices-ffa726?style=flat-square)
![Zéro dépendance](https://img.shields.io/badge/Zéro-dépendance-ef5350?style=flat-square)

---

### 🎯 Khéops v4.3 — Localisation acoustique de drones

**Simulateur de goniométrie acoustique de drones par TDOA** sur une pyramide de 5 micros : chaîne ADC 1 MHz avec corrélation GCC-PHAT, trajectoire par moindres carrés glissants, caméra d'identification avec chronomètres, météo en direct, et onglet d'étude pour dimensionner la pyramide (temps de focus à 1° selon la taille de la base). Interface bilingue (langue du navigateur).

[![Lancer](https://img.shields.io/badge/▶_Lancer-Khéops_v4.3-66bb6a?style=for-the-badge)](https://ericperret.github.io/One-Page-One-Mission/kheops_v43.html)
[![Khéops](https://img.shields.io/badge/Khéops-Dépôt-4fc3f7?style=for-the-badge&logo=github)](https://github.com/ericperret/One-Page-One-Mission)
![TDOA](https://img.shields.io/badge/TDOA-GCC--PHAT-ffa726?style=flat-square)
![Zéro dépendance](https://img.shields.io/badge/Zéro-dépendance-ef5350?style=flat-square)

---

### 🚀 APPELS AUX TESTEURS (Besoin de 20 testeurs)

Je cherche des testeurs pour valider mes applications sur le Play Store.

1. **Rejoindre le groupe :** [Groupe Google azsfr](https://groups.google.com/g/azsfr)

2. **Retour :** Je teste votre app en retour ! Contactez-moi par email ou via une Issue.

---

### Ce que je construis

**Géosciences et simulation** — Modélisation de paléoglaciers, ruptures de barrage en hydrodynamique 2D (Saint-Venant), traitement des MNT Copernicus, dispersion balistique et gazeuse  
**SIG et cadastre** — Visionneuse cadastrale DXF-PCI, index des rues et numéros, division de parcelles, exports géomètre  
**Détection et identification de drones** — Écoute WiFi multi-protocole, balise ODID, intégration ADS-B, prédiction de trajectoire, localisation acoustique TDOA  
**Traitement du signal** — Localisation acoustique, TDOA, GCC-PHAT, chaînes de transmission DVB-S, SSTV, antennes  
**Cryptanalyse** — Cassage de chiffrements classiques, score par n-grammes, recuit simulé, Kryptos / Zodiac  
**Génie parasismique** — Isolation sismique à la base, optimisation prix / risque, plan de pose des dispositifs  
**Santé** — Triage pédiatrique (approuvé par des médecins urgentistes), questionnaire d'auto-orientation, musicothérapie  
**Enseignement** — Apprentissage du SQL, préparation aux examens drone et aéronautique, outils de maths et de lecture pour l'école primaire

### Démos en ligne

| Projet | Lancer | Description |
|---------|--------|-------------|
| [**obd**](https://github.com/ericperret/obd) | — | 🚗 Passerelle CAN OBD-II — diagnostic, écoute CAN et interface web — ESP32-S3 |
| [**DroneRX**](https://github.com/ericperret/DroneRX) | — | 🚁 Détection de drones multi-protocole — FR/ODID/DJI/Parrot — ESP32-S3 + ADS-B |
| [**quizz**](https://github.com/ericperret/quizz) | [▶️ tous les outils](https://ericperret.github.io/quizz/index2.html) | 🎓 Examens drone et aéronautique, outils scolaires, ⭐ triage pédiatrique, jeux |
| [**CREST**](https://github.com/ericperret/crest) | [▶️ carte](https://ericperret.github.io/crest/map.html) | 🏔️ Relief 3D, paléoglaciers et rupture de barrage (Saint-Venant 2D, validé sur Malpasset) |
| [**Sismic**](https://github.com/ericperret/Sismic) | [▶️ simulateur](https://ericperret.github.io/Sismic/simulateur_sismique.html) | 🏠 Isolation sismique d'une maison — courbe prix / risque et plan de pose des dispositifs (pendules, amortisseurs, butées), 21 séismes |
| [**dispersion**](https://github.com/ericperret/dispersion) | [▶️ v6.2](https://ericperret.github.io/dispersion/dispersion_v62.html) | 🚀 Dispersion balistique et gazeuse (CSG/Kourou et pas de tir du monde) — RK45, Pasquill-Gifford, vent en direct |
| [**cadastre**](https://github.com/ericperret/cadastre) | [▶️ inspecteur](https://ericperret.github.io/cadastre/cadastre_dxf_inspecteur_v21.html) | 🗺️ Visionneuse du cadastre DXF-PCI — rues et numéros, division de parcelles, export DA / GeoJSON |
| [**JPEG2DVB**](https://github.com/ericperret/JPEG2DVB) | [▶️ 15 étapes](https://ericperret.github.io/JPEG2DVB/index2.html) | 📡 Chaîne de transmission DVB-S pas à pas — de la DCT au QPSK et au SRRC |
| [**code**](https://github.com/ericperret/code) | [▶️ cracker](https://ericperret.github.io/code/multi_cipher_v3_24_0.html) · [▶️ bataille navale](https://ericperret.github.io/code/bataille_navale_v6.html) | 🔐 Multi-Cipher Cracker v3.24 (plus de 30 chiffrements classiques) · bataille navale cryptographique |
| [**sql_studio**](https://github.com/ericperret/sql_studio) | [▶️ SQL Studio](https://ericperret.github.io/sql_studio/sql_studio.html) | 🗄️ Apprentissage du SQL — interpréteur et base intégrés |
| [**One-Page-One-Mission**](https://github.com/ericperret/One-Page-One-Mission) | [▶️ Khéops](https://ericperret.github.io/One-Page-One-Mission/kheops_v43.html) | 🎯 Localisation acoustique de drones — TDOA, pyramide de 5 micros, GCC-PHAT, suivi caméra |
| [**sstv**](https://github.com/ericperret/sstv) | [▶️ outils](https://ericperret.github.io/sstv/index2.html) | 📻 Télévision à balayage lent — encodeur WAV, décodeur (fichier et direct), diagnostic |
| [**lpda**](https://github.com/ericperret/lpda) | [▶️ calculateur](https://ericperret.github.io/lpda/lpda_uhf.html) | 📶 Antenne log-périodique UHF — longueurs de coupe, angle optimal, plan de perçage |
| [**photo**](https://github.com/ericperret/photo) | [▶️ perspective](https://ericperret.github.io/photo/perspective-correction-filtres.html) | 📸 Six outils image et géodonnées — perspective, niveaux YUV, forensique JPEG, GeoTIFF, tuiles MNT |

---

### Philosophie
Analyse → Conception → Algorithme → Ensuite, le choix du langage.
Pas l'inverse.

Portable. Autonome. Aucun framework. Aucune étape de construction.  
On ouvre le fichier. Ça marche.

---

### Parcours

**2023 – aujourd'hui** — Ministère de l'Intérieur · Technicien SIC CS « Administrateur SIG »  
**2018 – 2022** — Ministère de l'Intérieur · Technicien SIC CN « Multimédia »  
**2003 – 2016** — AZS (fondateur) · Électronique pour la défense et la sécurité  
**1998 – 2003** — SOFIM · Ingénieur UNIX, haute disponibilité (HACMP)  
**1996 – 1997** — Thaï Radiators · ISO 9001, création du laboratoire d'essais  
**1994 – 1996** — IBM · Production en salle blanche, implantation ionique  
**1993** — Service national, Sécurité civile  
**1992** — ESI Sup'info · Analyste programmeur  
**1989** — Concours de médecine (Nancy) · Admis  
**1988** — Baccalauréat C · Nancy-Metz

---

### Certifications et licences

📻 Radioamateur F1OCM depuis 1986, aujourd'hui FY4AY  
✈️ Formation pilote privé  
⛵ Permis bateau côtier  
🤿 Plongée niveau 1  
⚡ Habilitation électrique BR-B2V  
🏗️ CACES R386 1B, 3B (PEMP)  
🚁 Drone CATS et BAPD (A1/A3 + A2)  
🚑 Secourisme et sécurité incendie

---

<sub>Guyane 🇬🇫</sub>
