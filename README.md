# MuGen-100: A Diverse and Globally-Rich Music Genre Dataset

**MuGen-100** is a large-scale, globally representative dataset designed to support research and development in music genre classification. It emphasizes genre diversity, cultural inclusion, and data quality. It was created to support genre-aware audio applications and benchmarking machine learning models.

---

## 📦 Dataset Download

The dataset can be downloaded via the following link:

**[Download MuGen-100 Dataset](https://alakhawayn365my.sharepoint.com/:f:/g/personal/r_zouitni_aui_ma/Es2PWQFrsfpFghCIgiXZ9NkBmucRMhE27F0gbwyO-KZzWA?e=FnDAOm)**

---

## 📊 Dataset Overview

- **Total Size:** 43.5 GB (complete dataset)  
- **Genres:** 100 distinct music genres from around the world  
- **Clips per Genre:** 100 audio clips  
- **Clip Duration:** 30 seconds  
- **Total Clips:** 10,000  
- **Audio Format:** `.wav`  

---

## 🛠️ Data Collection Process

1. Scraped playlist links via **YouTube Data API**, public archives, and Kaggle benchmark datasets.  
2. Extracted 30-second `.wav` segments using **pydub** for precise slicing.  
3. Organized into cleanly labeled folders, one per genre.

For a list of all 100 genres with descriptions and regional origins, see `genres.txt`.

---

## 📁 Dataset Versions

MuGen-100 is structured into three subsets:

- **Mini Set** (10 genres × 100 samples): Ideal for quick prototyping  
- **Lite Set** (50 genres × 100 samples): Balanced for mid-scale development  
- **Full Set** (100 genres × 100 samples): Comprehensive and large-scale benchmarking

---

## 📂 Folder Structure

<details>
<summary><strong>📁 MuGen-100</strong></summary>

```text
MuGen-100/
├── mini/
│   ├── Caribbean - Reggae
│   ├── East Europe - Turbo Folk
│   ├── Japan - Jpop
│   ├── Latin America - Mariachi
│   └── ...
│
├── lite/
│   ├── Africa/
│   │   ├── Central Africa - Bikutsi
│   │   └── ...
│   ├── Asia/
│   │   ├── India - Carnatic
│   │   └── ...
│   ├── Europe & North America/
│   │   └── ...
│   ├── Latin America & Caribbean/
│   │   └── ...
│   └── Middle East & North Africa/
│       └── ...
│
└── full/
    ├── Caribbean - Reggae
    ├── Central Africa - Makossa
    ├── China - Guqin
    ├── Latin America - Tango
    ├── Middle East - Dabke
    ├── North Africa - Aita
    ├── North America - Rock
    ├── South Africa - Kwaito
    ├── Turkey - Turkish Classical
    └── ...
