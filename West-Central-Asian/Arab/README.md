# Arab Maqam & Arab-Andalusian Music Information Retrieval & Generation Paper Collection

A curated, comprehensive collection of research papers, datasets, and computational resources for the analysis, recognition, and generative modeling of Arab music traditions, encompassing both Eastern (*Mashriq*) *Maqam* repertoires and North African (*Maghreb*) *Arab-Andalusian* (*al-Āla* / *Nawba*) traditions.

## 📖 Overview
Arab classical and traditional music is defined by the *Maqam* modal system—built on microtonal intervals (including quarter-tones and neutral seconds), characteristic melodic pathways (*sayr*), and tetrachordal/pentachordal building blocks (*ajnas*)—alongside cyclic rhythmic modes (*Iqa'at*) and improvisational forms (*Taqsim*, *Layali*). In the Maghreb, the *Arab-Andalusian* tradition organizes repertoire into multi-movement suites (*Nawbat*) governed by diatonic modal frameworks (*Ṭubūʿ*) and progressive rhythmic phases (*Mīzān*). Because these traditions rely heavily on oral transmission, heterophonic textures, and microtonal intonation outside 12-TET, standard Western MIR models require specialized computational approaches.

---

## 📋 Table of Contents
- [Datasets & Corpora](#-datasets--corpora)
- [Research Papers](#-research-papers)
  - [Foundations and Databases](#foundations-and-databases)
  - [Maqam, Mode & Melodic Analysis](#maqam-mode--melodic-analysis)
  - [Regional Genre & Classification](#regional-genre--classification)
  - [Generation and Artificial Intelligence](#generation-and-artificial-intelligence)
- [License & Citation](#license--citation)

---

## 🗄 Datasets & Corpora
Links to the primary verified data sources used in the field.

| Dataset | Type | Description | Link |
| :--- | :--- | :--- | :--- |
| **Arab-Andalusian Music Corpus** | Audio/Metadata | 164 concert recordings (>125 hours, 8.9 GB) of Moroccan *al-Āla* (*Arab-Andalusian*) music collected by the CompMusic project. | [Zenodo Archive](https://zenodo.org/records/1291776) / [Dunya Portal](https://dunya.compmusic.upf.edu/andalusian) |
| **Arab-Andalusian Music Lyrics Dataset** | Text/Annotations | Companion lyrics and metadata corpus aligned with the CompMusic Arab-Andalusian audio collection. | [Zenodo Archive](https://doi.org/10.5281/zenodo.3337623) |
| **1932 Cairo Congress of Arab Music Dataset** | Metadata/Features | Structured metadata, *maqam*/*iqa'* tags, tonic annotations, and pitch histograms extracted from historical recordings of the 1932 Cairo Congress. | [Zenodo Archive](https://zenodo.org/records/15682346) |
| **YMIR / YMGD (Yemeni Music Dataset)** | Audio | Expert-annotated benchmark of 1,475 audio clips across five traditional Yemeni genres (*Sana'ani*, *Hadhrami*, *Lahji*, *Tihami*, *Adeni*). | [Zenodo Archive](https://doi.org/10.5281/zenodo.19543208) |

---

## 📄 Research Papers

### Foundations and Databases
* [**An Open Research Dataset of the 1932 Cairo Congress of Arab Music**](https://arxiv.org/abs/2506.14503) – *B. Bozkurt (ArXiv, 2025)*
* [**Creating Corpora for Computational Research in Arab-Andalusian Music**](https://repositori.upf.edu/items/4342290b-7eb8-4a05-bf76-b1a65670931a?locale=en) – *M. Sordo, A. Chaachoo, & X. Serra (1st Int. Workshop on Digital Libraries for Musicology, 2014)*

---

### Maqam, Mode & Melodic Analysis
* [**Nawba Recognition for Arab-Andalusian Music Using Templates From Music Scores**](https://zenodo.org/records/1257388) – *N. Pretto, B. Bozkurt, R. Caro Repetto, & X. Serra (SMC, 2018)*
* [**Contributing to New Musicological Theories with Computational Methods: The Case of Centonization in Arab-Andalusian Music**](https://repositori.upf.edu/items/cdfe380d-608c-4c25-aae2-4b3be4c234d3?locale=en) – *T. Nuttall, M. García-Casado, V. Núñez-Tarifa, R. Caro Repetto, & X. Serra (ISMIR, 2019)*
* [**Classifying Maqams of Qur'anic Recitations Using Deep Learning**](https://repository.aus.edu/bitstreams/8d4f4330-13ad-4c4a-b235-0719d21ccf2c/download) – *S. Shahriar & U. Tariq (IEEE Access, 2021) – [Introduces the Maqam-478 dataset across 8 core maqamat]*

---

### Regional Genre & Classification
* [**YMIR: A New Benchmark Dataset and Model for Arabic Yemeni Music Genre Classification Using Convolutional Neural Networks**](https://arxiv.org/abs/2604.05011) – *M. AL-Makhlafi, A. A. AlKannad, E. Almekhlafi, N. Q. Othman Ahmed Mohammed, & S. Qaid (ArXiv, 2026)*

---

### Generation and Artificial Intelligence
* [**MazzikaAI: A Knowledge-Based Performance-to-Prompt Compiler for Real-Time Arabic Maqam Accompaniment with a Streaming Text-to-Music Model**](https://arxiv.org/abs/2608.10360) – *J. Du, B. Abdeljaouad, Y. Zhuang, & H. Li (ArXiv, 2026)*

---

## License & Citation
This curated list is licensed under the **CC-BY-4.0 License**.

If you use this repository for your research, please cite it as follows:
```text
Diba Hadi Esfangereh. (2026). Culturally-Grounded-MIR: A Comprehensive Research Hub. GitHub.
```