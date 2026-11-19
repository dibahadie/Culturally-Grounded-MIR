# East-Asian Music Information Retrieval & Generation Paper Collection

A curated, comprehensive collection of research papers, datasets, and computational resources for the analysis, recognition, and generative modeling of East Asian traditional music, focusing primarily on Chinese, Japanese, and Korean traditions.

## 📖 Overview
East-Asian traditional music encompasses highly diverse traditions, including Chinese *Jingju* (Beijing Opera) and *Guqin*, Japanese *Gagaku* and *Shakuhachi*, and Korean *Gugak* and *Pansori*. Key computational challenges include analyzing pentatonic and heptatonic pitch frameworks, unmetered or free rhythm structures (such as *jobuki* in Gagaku or *beompae* in Korean music), heterophonic textures, and oral or tablature-based notations. This repository serves as a central hub for researchers tackling these unique MIR challenges.

---

## 📋 Table of Contents
- [Datasets & Corpora](#-datasets--corpora)
- [Research Papers](#-research-papers)
  - [Foundations and Databases](#foundations-and-databases)
  - [Melody, Tuning & Transcription Analysis](#melody-tuning--transcription-analysis)
  - [Rhythm, Timing & Structural Analysis](#rhythm-timing--structural-analysis)
  - [Generation and Artificial Intelligence](#generation-and-artificial-intelligence)
- [License & Citation](#license--citation)

---

## 🗄 Datasets & Corpora
Links to the primary verified data sources used in the field.

| Dataset | Type | Description | Link |
| :--- | :--- | :--- | :--- |
| **Jingju Music Scores Collection** | Symbolic | A machine-readable collection of 92 *Jingju* (Beijing Opera) scores transcribed into MusicXML format by the CompMusic project. | [CompMusic Archive](https://compmusic.upf.edu/node/348) |
| **Jingju A Cappella Dataset** | Audio/Metadata | A dataset of 120 arias consisting of unaccompanied Beijing Opera singing, explicitly built for intonation and evaluation research. | [ArXiv / UPF](https://arxiv.org/pdf/1708.03986) |
| **Guqin-Dataset** | Symbolic | An open-source symbolic music dataset of *Guqin* tablature and numbered musical notation in MusicXML format. | [GitHub](https://github.com/lukewys/Guqin-Dataset) |
| **Gugak Acoustic Descriptor Corpus** | Audio | A 3.6 GB segment-level dataset of Korean traditional music (*Gugak*) curated for MIR and digital heritage analysis. | [Zenodo Archive](https://zenodo.org/records/19964647) |
| **Gugak-VocalSet** | Audio | A multi-genre, studio-quality dataset of Korean traditional vocal music, including *Pansori*. | [ArXiv](https://arxiv.org/html/2610.15350v1) |

---

## 📄 Research Papers

### Foundations and Databases
* [**Creating a Corpus of Jingju (Beijing Opera) Music and Possibilities for Melodic Analysis**](https://archives.ismir.net/ismir2014/paper/000237.pdf) – *R. Caro Repetto & X. Serra (ISMIR, 2014)*
* [**A Collection of Music Scores for Corpus Based Jingju Singing Research**](https://archives.ismir.net/ismir2017/paper/000119.pdf) – *R. Caro Repetto & X. Serra (ISMIR, 2017)*
* [**Making Japanese Imperial Court Music Scores Machine-Readable: Encoding of Hichiriki Notation as a Case Study**](https://journals.openedition.org/jtei/5480) – *S. Seki (Journal of the Text Encoding Initiative, 2025)*

---

### Melody, Tuning & Transcription Analysis
* [**Pitch Contour Segmentation for Computer-Aided Jingju Singing Training**](https://repositori.upf.edu/server/api/core/bitstreams/ef4c034a-ed6d-4ba1-ad57-343e0784f05e/content) – *R. Gong, Y. Yang, & X. Serra (SMC, 2016)*
* [**Audio to Score Matching by Combining Phonetic and Duration Information**](https://archives.ismir.net/ismir2017/paper/000045.pdf) – *R. Gong, J. Pons, & X. Serra (ISMIR, 2017)*
* [**Automatic Alignment of Long Syllables in a Cappella Beijing Opera**](https://arrow.tudublin.ie/cgi/viewcontent.cgi?article=1017&context=fema) – *G. Dzhambazov, Y. Yang, R. Caro Repetto, & X. Serra (FMA, 2016)*

---

### Rhythm, Timing & Structural Analysis
* [**Analysis of Unmetered Coordination in the Tōgaku Ensemble of Japanese Court Music (Gagaku)**](https://journal.iftawm.org/previous/2025-volume-13-no-2/clayton_kamata-2025/) – *M. Clayton & S. Kamata (Analytical Approaches to World Music, 2025)*
* [**Transcription and Recognition of Syllable based Percussion Patterns: The Case of Beijing Opera**](https://compmusic.upf.edu/ismir-2014-bo) – *A. Srinivasamurthy, R. Caro Repetto, et al. (ISMIR, 2014)*

---

### Generation and Artificial Intelligence
* [**Adapting a Latent Audio Diffusion Model to Historical Guqin Recordings: A Listening-Driven Case Study**](https://arxiv.org/html/2610.07486v1) – *H. Cai (ArXiv, 2026)*
* [**GANkyoku: a Generative Adversarial Network for Shakuhachi Music**](https://arxiv.org/abs/1911.10119) – *O. Peracha & S. Head (ArXiv, 2019)*

---

## License & Citation
This curated list is licensed under the **CC-BY-4.0 License**.

If you use this repository for your research, please cite it as follows:
```text
Diba Hadi Esfangereh. (2026). Culturally-Grounded-MIR: A Comprehensive Research Hub. GitHub.
```