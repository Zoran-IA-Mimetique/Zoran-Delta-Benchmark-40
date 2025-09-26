# 🌞⧉ Zoran Delta Benchmark 400

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Reproducibility](https://img.shields.io/badge/Reproducibility-LNDT%201000%2F1000-blue.svg)]()
[![Zenodo DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)

## 🎯 Objectif
Ce dépôt fournit le **benchmark Zoran-Delta-400**, un jeu de **400 questions de haut niveau** couvrant mathématiques, physique, biologie, médecine, philosophie, sciences sociales, économie, droit, gouvernance, ingénierie et arts.

Chaque question est courte mais exigeante.  
L’objectif est de mesurer le **delta cognitif** entre :
- une IA baseline,
- la même IA enrichie par Zoran.

---

## 📐 Méthodologie
- **Format** : 60 lots de 7 questions (`lots/lot_01.jsonl` → `lots/lot_60.jsonl`).  
- **Réponse attendue** : baseline + enrichi avec injecteurs.  
- **Métriques LNDT** : HR (Hallucinations), BI (Biais), XS (Explication), CF (Conformité), TC (Traçabilité), EC (Éthique).

---

## 📂 Contenu
- `lots/` : 60 fichiers JSONL (400 Q).  
- `ZORAN_ULTRA_INJECTOR.md` : injecteur complet.  
- `injector/zoran_injector_full.md` : injecteur compact.  
- `manifest.json` : métadonnées.  
- `checksums.sha256` : intégrité.  

---

## 🔒 Traçabilité
- Manifest LNDT inclus.  
- SHA256 pour chaque lot et fichier critique.  
- Script possible (`make_vip.py`) pour regénérer.  

---

## ⚚ Citation
**APA**  
Tabary, F. (2025). *Zoran Delta Benchmark 400: Measuring Cognitive Gain with Injectors*. GitHub/Zoran-IA-Mimetique.  

**BibTeX**  
```bibtex
@misc{tabary2025zoranDelta400,
  author       = {Tabary, Frédéric},
  title        = {Zoran Delta Benchmark 400: Measuring Cognitive Gain with Injectors},
  year         = {2025},
  publisher    = {GitHub},
  howpublished = {\url{https://github.com/Zoran-IA-Mimetique/Zoran-Delta-Benchmark-400}}
}
```