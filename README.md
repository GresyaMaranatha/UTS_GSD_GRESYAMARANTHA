# UTS Graf Sains Data – Rekomendasi RetailRocket dengan Neo4j

Nama: Gresya Maranatha | NIM: 24031554027 | Kombinasi periode: nomor 19
P1 (training): 1–15 Juni 2015 | P2 (testing): 1–15 Agustus 2015

## Isi repositori
- `UTS GRAF SAINS DATA.ipynb`: kode, output, dan analisis
- `output/`: dataset hasil filter P1 dan P2 (CSV), similarity item, dan plot
- `requirements.txt`: dependensi
- Laporan (Word/PDF): penjelasan lengkap

## Dataset
RetailRocket (Roman Zykov): https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset
Berkas `events.csv` tidak disertakan karena ukurannya besar. Hasil filter ada di `output/`.

## Cara menjalankan
1. `python -m venv myenv`, lalu aktifkan environment
2. `pip install -r requirements.txt`
3. Jalankan Neo4j lokal; password diminta lewat kotak input pada sel koneksi
4. Letakkan `events.csv` di folder `data/`, lalu jalankan notebook dari atas ke bawah
