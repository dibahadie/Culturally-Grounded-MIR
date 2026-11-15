# Turkish Music Information Retrieval & Generation Paper Collection

A curated, comprehensive collection of research papers, datasets, and computational resources for the analysis, recognition, and generative modeling of Ottoman-Turkish Classical and Folk music.

## 📖 Overview
Turkish music is built upon the *Makam* system and *Usul* rhythmic cycles, utilizing a microtonal interval system (typically modeled via 24-tone Arel-Ezgi-Uzdilek theory) that challenges standard Western MIR techniques.

---

## 📋 Table of Contents
- [Datasets & Corpora](#-datasets--corpora)
- [Research Papers](#-research-papers)
  - [Foundations, Databases & Tools](#foundations-databases--tools)
  - [Automatic Makam, Pitch & Melodic Analysis](#automatic-makam-pitch--melodic-analysis)
  - [Rhythm, Usul & Structural Analysis](#rhythm-usul--structural-analysis)
  - [Automatic Transcription & Lyrics Alignment](#automatic-transcription--lyrics-alignment)
  - [Generation and Artificial Intelligence](#generation-and-artificial-intelligence)
  - [Musicology, Theory & Theses](#musicology-theory--theses)
- [License & Citation](#-license--citation)

---

## 🗄 Datasets & Corpora
Links to the primary data sources used in the field.

| Dataset | Type | Description | Link |
| :--- | :--- | :--- | :--- |
| **SymbTr** | Symbolic | The largest machine-readable collection of Makam scores (2200+ pieces). | [GitHub](https://github.com/MTG/SymbTr) |
| **Dunya Makam** | Audio/Score | A web-based corpus exploration tool and dataset by CompMusic. | [Dunya Portal](https://dunya.compmusic.upf.edu/makam/) |
| **OTMM** | Audio | Dataset for Makam recognition and Tonic Identification. | [GitHub](https://github.com/MTG/otmm_makam_recognition_dataset) |
| **Turkish Makam Phrases** | Symbolic | A symbolic dataset of Turkish makam music phrases. | [FMA Proceedings](https://compmusic.upf.edu/node/237) |

---

## 📄 Research Papers

### Foundations, Databases & Tools

* [**A Culture-Specific Analysis Software for Makam Music Traditions**](https://mtg.upf.edu/system/files/publications/FMA2015_bilgemiracatici_fullpaper.pdf) – *B. M. Atıcı, B. Bozkurt, & S. Şentürk (FMA, 2015)*
* [**A Corpus for Computational Research of Turkish Makam Music**](http://hdl.handle.net/10230/35358) – *B. Uyar, H. S. Atlı, S. Şentürk, B. Bozkurt & X. Serra (ATMM, 2014)*
* [**A Symbolic Dataset of Turkish Makam Music Phrases**](https://www.researchgate.net/publication/283123469_A_SYMBOLIC_DATASET_OF_TURKISH_MAKAM_MUSIC_PHRASES) – *M. K. Karaosmanoğlu, B. Bozkurt, A. Holzapfel, & N. Doğrusöz Dişiaçık (FMA, 2014)*
* [**A Turkish Makam Music Symbolic Database for Music Information Retrieval: SymbTr**](https://zenodo.org/records/15470412) – *M. K. Karaosmanoğlu (ISMIR, 2012)*
* [**Music Information Retrieval for Turkish Music: Problems, Solutions and Tools**](https://doi.org/10.1109/siu.2009.5136518) – *B. Bozkurt, A. C. Gedik, & M. K. Karaosmanoğlu (SIU, 2009)*

---

### Automatic Makam, Pitch & Melodic Analysis

* [**An Automatic Pitch Analysis Method for Turkish Maqam Music**](https://doi.org/10.1080/09298210802259520) – *B. Bozkurt (JNMR, 2008)*
* [**Pitch-Frequency Histogram-Based Music Information Retrieval for Turkish Music**](https://www.sciencedirect.com/science/article/abs/pii/S0165168409002898) – *A. C. Gedik & B. Bozkurt (Signal Processing, 2010)*
* [**Weighing Diverse Theoretical Models on Turkish Maqam Music Against Pitch Measurements**](https://www.tandfonline.com/doi/abs/10.1080/09298210903147673) – *B. Bozkurt, O. Yarman, M. K. Karaosmanoğlu, & C. Akkoç (JNMR, 2009)*
* [**N-gram Based Statistical Makam Detection on Makam Music in Turkey Using Symbolic Data**](https://zenodo.org/records/1417459) – *E. Ünal, B. Bozkurt & M. K. Karaosmanoğlu (2012)*
* [**A Method for Tonic Frequency Identification of Turkish Makam Music Recordings**](https://mtg.upf.edu/system/files/publications/FMA2015_HSercanATLI_full-paper.pdf) – *H. S. Atlı, B. Bozkurt, & S. Şentürk (FMA, 2015)*
* [**Computational Analysis of Overall Melodic Progression for Turkish Makam Music**](https://web.archive.org/web/20200228091321/https://zenodo.org/record/1211460/files/2015_1_PenserLimprovisation_Bozkurt.pdf) – *B. Bozkurt (Penser l’improvisation, 2015)*

---

### Rhythm, Usul & Structural Analysis

* [**Usul and Makam Driven Automatic Melodic Segmentation for Turkish Music**](https://www.researchgate.net/publication/265857397_Usul_and_Makam_driven_automatic_melodic_segmentation_for_Turkish_music) – *B. Bozkurt, M. K. Karaosmanoğlu, B. Karaçalı, & E. Ünal (JNMR, 2014)*
* [**Section-Level Modeling of Musical Audio for Linking Performances to Scores in Turkish Makam Music**](https://www.di.ens.fr/~simsekli/resources/icassp_15_holzapfel.pdf) – *A. Holzapfel, U. Şimşekli, S. Şentürk, & A. T. Cemgil (ICASSP, 2015)*
* [**Relation Between Surface Rhythm and Rhythmic Modes in Turkish Makam Music**](https://www.tandfonline.com/doi/abs/10.1080/09298215.2014.939661) – *A. Holzapfel (JNMR, 2015)*
* [**Rhythmic Similarity in Traditional Turkish Music**](https://archives.ismir.net/ismir2009/paper/000056.pdf) – *A. Holzapfel & Y. Stylianou (ISMIR, 2009)*

---

### Automatic Transcription & Lyrics Alignment

* [**Automatic Transcription of Turkish Makam Music**](https://repositori.upf.edu/server/api/core/bitstreams/dbf8c6be-8934-4275-8d0a-f565a447fa0c/content) – *E. Benetos & A. Holzapfel (ISMIR, 2013)*
* [**Automatic Transcription of Turkish Microtonal Music**](https://pubs.aip.org/asa/jasa/article-abstract/138/4/2118/899017/Automatic-transcription-of-Turkish-microtonal?redirectedFrom=fulltext) – *E. Benetos & A. Holzapfel (JASA, 2015)*
* [**Automatic Lyrics-to-Audio Alignment in Classical Turkish Music**](https://repositori.upf.edu/server/api/core/bitstreams/99da1194-67a7-4d79-8980-899f07e8db71/content) – *G. Dzhambazov, S. Şentürk, & X. Serra (FMA, 2014)*
* [**On the Use of Note Onsets for Improved Lyrics-to-Audio Alignment in Turkish Makam Music**](https://archives.ismir.net/ismir2016/paper/000243.pdf) – *G. Dzhambazov, A. Srinivasamurthy, S. Şentürk, & X. Serra (ISMIR, 2016)*
* [**Composition Identification in Ottoman-Turkish Makam Music Using Transposition-Invariant Partial Audio-Score Alignment**](https://sertansenturk.com/uploads/publications/senturk2016compositionIdentification_smc.pdf) – *S. Şentürk & X. Serra (2016)*
* [**Computational Analysis of Turkish Makam Music: Review of State-of-the-Art and Challenges**](https://repositori.upf.edu/server/api/core/bitstreams/241e6a71-63c9-4de5-976e-7ff968a579c1/content) – *B. Bozkurt, R. Ayangil, & A. Holzapfel (JNMR, 2014)*

---

### Generation and Artificial Intelligence

* [**TuFoC: Regional Classification of Turkish Folk Music Recordings Using Deep Learning**](https://www.semanticscholar.org/paper/TuFoC%3A-regional-classification-of-Turkish-folk-deep-Abidin/7007887f0d6ab68ac49d3582f2196295f36191b2) – *D. Abidin*
* [**A Classification Study for Turkish Folk Music Makam Recognition Using Machine Learning with Data Augmentation Techniques**](https://dl.acm.org/doi/abs/10.1007/s00521-023-09177-6) – *A. Börekci & O. Sevli (2023)*
* [**Turkish Music Generation using Deep Learning**](https://ieeexplore.ieee.org/document/9302283) – *S. Özkan et al. (2020)*
* [**Usage of Data Mining for Makam Recognition in Classical Turkish Music**](https://doi.org/10.17341/gazimmfd.369557) – *D. Abidin, Ö. Öztürk, & T. Özacar Öztürk (Journal of the Faculty of Engineering and Architecture of Gazi University, 2017)*

---

## License & Citation
This curated list is licensed under the **CC-BY-4.0 License**.

If you use this repository for your research, please cite it as follows:
```text
Diba Hadi Esfangereh. (2026). Culturally-Grounded-MIR: A Comprehensive Research Hub. GitHub.