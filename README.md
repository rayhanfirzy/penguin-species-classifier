# Penguin Species Classifier

Prediksi spesies penguin (Adelie, Chinstrap, atau Gentoo) berdasarkan fitur fisik menggunakan Machine Learning, lengkap dengan API FastAPI (deployment) dan monitoring performa.

## Isi

* `penguin_analysis_full.ipynb` - analisis data, pelatihan model, deployment, dan monitoring.
* `deployment/` - API, modul fitur, modul monitoring, dan model tersimpan.
* `penguins_size.csv` - dataset penguin.

## Cara Menjalankan

1. Taruh notebook dan `penguins.csv` di folder yang sama.
2. Jalankan sel instalasi: `pip install fastapi uvicorn httpx pydantic joblib scipy scikit-learn`
3. Kernel -> Restart & Run All.

## Data

Dataset `penguins.csv` diambil dari Kaggle:

* **Judul dataset**: Palmer Archipelago (Antarctica) penguin data
* **Pembuat**: Kirsten Gorman / Parul Pandey
* **Link**: [Kaggle Palmer Penguins Dataset](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data)
* **Lisensi**: CC0: Public Domain
