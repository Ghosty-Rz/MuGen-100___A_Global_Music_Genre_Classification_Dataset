MuGen-100 is a large-scale, globally representative dataset designed to support research and development in music genre classification. It emphasizes genre diversity, cultural inclusion, and data quality. It was created for the purpose of building genre-aware audio applications and benchmarking machine learning models.

The Dataset can be downlaoded via the following link : 
" https://alakhawayn365my.sharepoint.com/:f:/g/personal/r_zouitni_aui_ma/Es2PWQFrsfpFghCIgiXZ9NkBmucRMhE27F0gbwyO-KZzWA?e=FnDAOm "

Dataset Overview:
Total Size: 43.5 GB (For the complete Dataset)
Genres: 100 distinct music genres from around the world
Clips per Genre: 100 audio clips
Clip Duration: 30 seconds
Total Clips: 10,000
Audio Format: .wav

Data Collection Process:
. Scrape playlist links through Youtube Data API + public archives + benchmark Datasets on Kaggle.
. Segment into 30s .wav clips: Extracted three 30-second segments per song. Used pydub to handle precise slicing and
exporting.
. Saved in structured folders per genre, labeled cleanly.

For the list of all 100 genres with short descriptions and regional origins, refer to the genres.txt file.

MuGen-100 is organized into three versions for varying use cases:

- The mini set (10 genres × 100 samples) is ideal for quick prototyping.
- The lite version (50 genres × 100 samples) balances diversity and efficiency for mid-scale development. 
- The full set (100 genres × 100 samples) is designed for large-scale training and benchmarking with comprehensive global coverage.

Folder Structure:
MuGen-100/
├── mini/                           
│   ├── Caribbean - Reggae
│   ├── East Europe - Turbo Folk
│   ├── Japan - Jpop
│   ├── Latin America - Mariachi
│   ├── Middle East - Khaleeji
│   ├── North Africa - Malhoun
│   ├── North America - Blues
│   ├── South Africa - Amapiano
│   ├── Southeast Asia - Luk Thung
│   └── West Europe - Flamenco

├── lite/                             
│   ├── Africa/
│   │   ├── Central Africa - Bikutsi
│   │   ├── Central Africa - Makossa
│   │   ├── East Africa - Benga
│   │   ├── North Africa - Balad
│   │   ├── North Africa - Gnawa
│   │   ├── North Africa - Rai
│   │   ├── South Africa - Amapiano
│   │   ├── South Africa - Kwaito
│   │   ├── West Africa - Griot
│   │   └── West Africa - Highlite
│
│   ├── Asia/
│   │   ├── China - Guqin
│   │   ├── China - Pekinopera
│   │   ├── India - Carnatic
│   │   ├── India Pakistan - Ghazal
│   │   ├── Japan - City Pop
│   │   ├── Japan - Jpop
│   │   ├── Korea - Gugak
│   │   ├── Korea - Kpop
│   │   ├── Southeast Asia - Dangdut
│   │   └── Southeast Asia - Luk Thung
│
│   ├── Europe & North America/
│   │   ├── East Europe - Balkan Brass
│   │   ├── East Europe - Turbo Folk
│   │   ├── Europe - Gypsy
│   │   ├── Europe - Opera
│   │   ├── North America - Blues
│   │   ├── North America - Country
│   │   ├── North America - Jazz
│   │   ├── North America - RnB
│   │   ├── West Europe - Chanson
│   │   └── West Europe - Flamenco
│
│   ├── Latin America & Caribbean/
│   │   ├── Caribbean - Bombayplena
│   │   ├── Caribbean - Reqqae
│   │   ├── Latin America - Cumbia
│   │   ├── Latin America - Mariachi
│   │   ├── Latin America - Merengue
│   │   ├── Latin America - Rumba
│   │   ├── Latin America - Salsa
│   │   ├── Latin America - Sertanejo
│   │   ├── Latin America - Son Jarocho
│   │   └── Latin America - Tango
│
│   └── Middle East & North Africa/
│       ├── Middle East - Classical Tarab
│       ├── Middle East - Khaleeji
│       ├── Middle East - Sufi
│       ├── Middle East - Dabke
│       ├── North Africa - Ahidous
│       ├── North Africa - Andalussi
│       ├── North Africa - Balad
│       ├── North Africa - Egyptian Shaabi
│       ├── North Africa - Rai
│       └── North Africa - Reggada

└── full/                            
    ├── Caribbean - Bombayplena
    ├── Caribbean - Reggae
    ├── Central Africa - Bikutsi
    ├── Central Africa - Makossa
    ├── Central Africa - Soukous
    ├── China - Guqin
    ├── China - Old Cpop
    ├── China - Pekinopera
    ├── East Africa - African Taarab
    ├── East Africa - Benga
    ├── East Europe - Balkan Brass
    ├── East Europe - Slavic Folk
    ├── East Europe - Turbo Folk
    ├── Europe - Alps
    ├── Europe - Classical
    ├── Europe - Gypsy
    ├── Europe - Opera
    ├── Global - Disco
    ├── Global - EDM
    ├── Global - Lofi
    ├── Global - Metal
    ├── Global - Pop
    ├── India - Bollypop
    ├── India - Carnatic
    ├── India - Semiclassical
    ├── India Pakistan - Ghazal
    ├── Iran - Iranian Pop
    ├── Iran - Bandari
    ├── Iran - Persian Classical
    ├── Japan - City Pop
    ├── Japan - Enka
    ├── Japan - Jpop
    ├── Japan - Minyo
    ├── Korea - Gugak
    ├── Korea - Kpop
    ├── Latin America - Bachata
    ├── Latin America - Banda
    ├── Latin America - Cumbia
    ├── Latin America - Forro
    ├── Latin America - Joropo
    ├── Latin America - Mariachi
    ├── Latin America - Merengue
    ├── Latin America - Norteno
    ├── Latin America - Rumba
    ├── Latin America - Salsa
    ├── Latin America - Samba
    ├── Latin America - Sertanejo
    ├── Latin America - Son Cubano
    ├── Latin America - Son Jarocho
    ├── Latin America - Tango
    ├── Middle East - Classical Tarab
    ├── Middle East - Dabke
    ├── Middle East - Khaleeji
    ├── Middle East - Sufi
    ├── Nordic - Nordic Folk
    ├── Nordic - Samicjoik
    ├── North Africa - Ahidous
    ├── North Africa - Ahwach
    ├── North Africa - Aita
    ├── North Africa - Andalussi
    ├── North Africa - Baladi
    ├── North Africa - Chgouri
    ├── North Africa - Dakkamarrakchia
    ├── North Africa - Egyptian Shaabi
    ├── North Africa - Gnawa
    ├── North Africa - Hassani
    ├── North Africa - Issawa
    ├── North Africa - Malhoun
    ├── North Africa - Moroccan Chaabi
    ├── North Africa - Rai
    ├── North Africa - Reggada
    ├── North Africa - Taktouka Jabalya
    ├── North America - Blues
    ├── North America - Country
    ├── North America - Funk
    ├── North America - Hiphop
    ├── North America - Jazz
    ├── North America - Rap
    ├── North America - RnB
    ├── North America - Rock
    ├── Oceania - Didgeridoo
    ├── Oceania - Haka
    ├── South Africa - Amapiano
    ├── South Africa - Kwaito
    ├── South Africa - Mbaqanga
    ├── South Africa - Mbube
    ├── Southeast Asia - Dangdut
    ├── Southeast Asia - Gamelan
    ├── Southeast Asia - Luk Thung
    ├── Turkey - Turkish Classical
    ├── Turkey - Turkish Folk
    ├── West Africa - Afrobeats
    ├── West Africa - Griot
    ├── West Africa - Highlife
    ├── West Africa - Juju
    ├── West Africa - Mbalax
    ├── West Africa - Wassoulou
    ├── West Europe - Chanson
    ├── West Europe - Fado
    ├── West Europe - Flamenco



The dataset is intended for non-commercial academic use only.
We do not claiming ownership of the content.