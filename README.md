# Étude d’une installation électrique industrielle BT

**Distribution 400/230 V · Dimensionnement des câbles · Protections électriques · Schéma unifilaire**

Projet pédagogique en génie électrique — **Moustapha IBRAHIM DJAMA et Thomas DHUNARA**  
ECAM-EPMI — spécialité **ISE (Ingénieur en Système Électrique)**  
[Portfolio de Moustapha](https://portfolio-eta-ten-t34s52rvq8.vercel.app/)

---

## Présentation

Ce dépôt rassemble le cadre d’une étude pédagogique d’un tableau de distribution basse tension destiné à alimenter deux moteurs industriels et un circuit monophasé d’éclairage et de prises.

L’objectif est de constituer un dossier reproductible : **bilan des charges, calcul des courants, choix des câbles et protections, schéma unifilaire et documentation technique**.

**Statut : étude en cours de constitution et de vérification.** Les documents PDF rangés dans « Documents de référence » sont des **supports issus d’un projet tiers antérieur, anonymisés pour la confidentialité**. Ils ne doivent **pas être présentés comme des travaux originaux de Moustapha IBRAHIM DJAMA ou Thomas DHUNARA**. Les calculs, dessins et justifications devront être refaits ou contrôlés et documentés avant une remise au professeur.

## Données du cas d’étude

| Départ | Charge | Alimentation | Longueur indicative |
| --- | --- | --- | ---: |
| A | Moteur 5 kW | 400 V triphasé | 15 m |
| B | Moteur 2 kW | 400 V triphasé | 10 m |
| C | Éclairage et prises 2 kW | 230 V monophasé | 20 m |

**Réseau de référence :** 400/230 V, 50 Hz. Les puissances et longueurs proviennent du cas d’étude utilisé comme point de départ ; elles restent à justifier dans le dossier final.

## Travaux à réaliser

- Calcul des courants d’emploi et du bilan des charges.
- Choix et vérification des sections de câbles selon les conditions de pose, le courant admissible et les chutes de tension.
- Choix et justification des dispositifs de protection, avec étude de coordination.
- Vérification de la tenue au court-circuit à partir d’hypothèses explicites.
- Production d’un schéma unifilaire cohérent avec la note de calcul.
- Vérification de la nomenclature et préparation du dossier technique final.

## Démarche de calcul

Pour un moteur triphasé, le courant d’emploi peut être estimé par :

$$
I_b = \frac{P_{\mathrm{utile}}}{\sqrt{3}\,U\,\eta\,\cos\varphi}
$$

La vérification complète nécessite notamment le mode de pose, la température, le regroupement des câbles, le matériau et l’isolant, les dispositifs de protection et les conditions de défaut.

**Normes à examiner :** série IEC 60364 et, pour une application française, série NF C 15-100. Les éditions pertinentes devront être précisées selon le périmètre réel de l’étude.

## État des livrables

| Livrable | État |
| --- | --- |
| Bilan de puissance et calculs des courants | À reprendre et vérifier |
| Tableau de dimensionnement des câbles | À produire |
| Schéma unifilaire | Référence existante, à redessiner/vérifier |
| Sélection et justification des protections | À reprendre et vérifier |
| Nomenclature du matériel | Référence existante, à vérifier |
| Note de calcul finale | À rédiger |

## Organisation du dépôt

```text
Etude_installation_electrique_BT_Moustapha_IBRAHIM_DJAMA_Thomas_DHUNARA/
├── README.md
├── 01_Documents_de_reference_anonymises/
│   ├── Nomenclature_materiel_source_non_verifie.pdf
│   ├── Rapport_technique_source_non_verifie.pdf
│   └── Schema_unifilaire_source_non_verifie.pdf
├── 02_Schema_CAO_a_verifier/
│   └── Schema_vectoriel_reconstitue_depuis_PDF.dxf
└── A_LIRE_AVANT_REMISE.md
```

**Remarque sur le CAO :** le fichier DXF a été reconstitué à partir du schéma PDF anonymisé. Il sert de support graphique éditable et **ne remplace pas le fichier natif AutoCAD**. Les fichiers `DWG` et `BAK` du projet tiers n’ont pas été redistribués : leur contenu et leurs métadonnées personnelles ne pouvaient pas être entièrement contrôlés.

## Outils

- **Excel :** calculs et tableaux, lors de la reprise de l’étude.
- **Python :** possible automatisation de vérifications, à documenter si réellement utilisé.
- **Outil de DAO/CAO :** à préciser lors du redessin et de la validation du schéma.

## Participants au travail de reprise

**Moustapha IBRAHIM DJAMA** et **Thomas DHUNARA**  
Élèves-ingénieurs — ECAM-EPMI  
[Portfolio de Moustapha](https://portfolio-eta-ten-t34s52rvq8.vercel.app/)

---


