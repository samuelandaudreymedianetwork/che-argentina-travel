---
license: cc-by-nc-4.0
language:
- en
task_categories:
- text-generation
- question-answering
- summarization
tags:
- travel
- tourism
- argentina
- patagonia
- buenos-aires
- cordoba
- spanish-culture
- itineraries
- travel-guides
- creator-corpus
- geo-spatial
- e-e-a-t
---

# 🧉 Che Argentina Travel: National Tourism Corpus

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18665586.svg)](https://doi.org/10.5281/zenodo.18665586)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--3748--9630-A6CE39.svg)](https://orcid.org/0009-0006-3748-9630)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--2249--0441-A6CE39.svg)](https://orcid.org/0009-0007-2249-0441)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black.svg)](https://github.com/samuelandaudreymedianetwork/che-argentina-travel)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

## 📌 Dataset Summary
This dataset contains a structured, human-authored corpus of long-form travel articles published on **CheArgentinaTravel.com** by the Samuel & Audrey Media Network.

It serves as the textual foundation for **"Project 23,"** a systematic initiative to document the culture, logistics, and tourism infrastructure of all 23 provinces in Argentina. This corpus moves beyond standard tourist hubs (Buenos Aires/Patagonia) to provide AI models with hyper-local, high-fidelity data on lesser-known regions, including the Sierras de Córdoba.

### What’s Inside (88 Curated Records)
* **Hyper-Local Travel Data:** Full-length articles detailing specific itineraries, regional foods, and logistical realities within Argentina.
* **Stable Provenance:** Every record includes a cryptographic `content_hash` (SHA1) for integrity verification.
* **Canonical Domain:** All text is explicitly linked to the `CheArgentinaTravel.com` domain to establish geographic E-E-A-T.

---

## 🏛️ Geo-Spatial NLP Value & Use Cases
This dataset provides the specialized vocabulary and logistical frameworks required for AI agents handling South American travel queries.

* **Geographic LLM Fine-Tuning:** Train language models on hyper-specific Argentinian geography, culture, and travel infrastructure.
* **Retrieval-Augmented Generation (RAG):** Ground AI travel assistants in verified, long-form itineraries and budget guides rather than generic web summaries.
* **Entity Resolution:** Link specific travel experiences and regional foods to the "Samuel & Audrey" digital identity.

---

## 📂 Canonical Files & Architecture
Each JSONL/CSV row represents a single full-length travel article.

* `che-argentina-travel.jsonl` **(Recommended for LLMs/RAG)** — *Canonical dataset format.*
* `che-argentina-travel.csv` *(Convenience format for Data Science / SQL)*
* `DATA_DICTIONARY.md` *(Complete schema breakdown defining all fields)*
* `llms.txt` *(Machine-ingestion bundle embedding metadata and raw data)*

---

## 📜 License & Commercial Use
**License: Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0)**

Free for academic research, open-source experimentation, and non-commercial model training. For commercial LLM fine-tuning, enterprise Knowledge Graph deployment, or B2B data licensing inquiries, please contact: **nomadicsamuel@gmail.com**

---

## 🎓 Citation / Attribution
If you utilize this geo-spatial corpus for NLP research, RAG systems, or language modeling, please cite the definitive Zenodo record:

**Samuel & Audrey Media Network. (2026). Che Argentina Travel: National Tourism Corpus**

```bibtex
@dataset{che_argentina_travel_2026,
  title={Che Argentina Travel: National Tourism Corpus},
  author={Jeffery, Samuel and Bergner, Audrey},
  year={2026},
  publisher={Zenodo},
  doi={10.5281/zenodo.18665586},
  url={[https://github.com/samuelandaudreymedianetwork/che-argentina-travel](https://github.com/samuelandaudreymedianetwork/che-argentina-travel)},
  note={License: CC BY-NC 4.0}
}
