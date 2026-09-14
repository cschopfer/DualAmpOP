
# DualAmpOP

<!--
![Photo du montage](docs/images/hero.jpg)
-->

PCB pour un montage universel d'ampli OP double SOIC-8 dont le pinning est compatible LM358

**Statut :**  🟡 Prototype fonctionnel 

---

## Caractéristiques

- Compatible LM358, MCP6002, etc
- Fonction principale 2 amplis utilisable en serie ou individuelement 
- Alimentation : Vcc/GND ou Vcc-Vdd
- Interfaces : Multiple câblage possible (amp inverseur/non inverseur/suiveur/filtre/etc)

## Structure du repo

| Dossier | Contenu |
|---|---|
| `hardware/` | Projet KiCad, Gerbers, BOM |
| `simulation/` | Simulations LTspice / KiCad |
| `mechanical/` | Fichiers FreeCAD/Fusion, STL |
| `firmware/` | Code PlatformIO / Arduino |
| `docs/` | Photos, datasheets, notices |

## Bill of Materials (BOM)

Composants principaux (liste complète : [`hardware/bom/DualAmpOP.csv`](hardware/bom/DualAmpOP.csv))

| Réf. | Composant | Valeur | Boîtier | Qté |
|---|---|---|---|---|
| U1 | ... | ... | ... | 1 |
| R1-R4 | Résistance | ... | 0805 | 4 |

## Fabrication du PCB

Gerbers prêts à l'emploi dans [`PCB/exports/gerbers/`](PCB/exports/gerbers/), ou directement depuis la dernière [Release](../../releases).

- Nombre de couches : 2
- Finition : HASL
- Dimensions : ... x ... mm

<!--
## Impression 3D

Fichiers STL dans [`mechanical/stl/`](mechanical/stl/).

- Matériau conseillé : PETG / PLA
- Support : oui/non
- Hauteur de couche : 0.2 mm
-->

## Schémas et plans

- [Schéma électrique (PDF)](PCB/export/PDF/DualAmpOP_v2_0_schema)


## Historique des versions

Voir [CHANGELOG.md](CHANGELOG.md).


## Auteur

Cédric Schöpfer — [digipict.ch](https://digipict.ch)
