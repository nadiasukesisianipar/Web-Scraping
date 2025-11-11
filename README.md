# Web-Scraping - Metode Pengumpulan Data Digital (API)
---

## 🧠 Deskripsi Proyek
Proyek ini bertujuan untuk **mengumpulkan data digital melalui API (Application Programming Interface)** dari beberapa website populer di Indonesia.  
Data diambil menggunakan **Python** dan diolah menjadi bentuk terstruktur (DataFrame) agar dapat dianalisis lebih lanjut.  

Setiap anggota kelompok melakukan **web scraping berbasis API** pada berbagai sumber data digital dengan tujuan yang berbeda:  
- **Analisis pasar dan harga produk (OLX)**  
- **Pemantauan harga logam mulia (IndoGold)**  
- **Informasi akomodasi (Agoda)**  
- **Jadwal perjalanan (tiket.com)**  
- **Informasi penerbangan (FlightStats & FlightRadar24)**  

---

## 🧩 Metode Umum
1. **Inspect Element** untuk menemukan endpoint API di setiap situs.  
2. **Mengambil data dengan library `requests`** menggunakan metode HTTP `GET`.  
3. **Konversi hasil ke format JSON** menggunakan `json.loads()`.  
4. **Normalisasi dan tabulasi data** menggunakan `pandas.json_normalize()` dan `pd.DataFrame()`.  
5. **Seleksi & pembersihan kolom** agar data lebih relevan dan siap dianalisis.  

---

## 🧰 Library yang Digunakan
| Library | Fungsi |
|----------|---------|
| **requests** | Mengakses dan mengambil data dari API menggunakan metode HTTP |
| **json** | Mengonversi response API ke dalam format JSON Python |
| **pandas** | Menyusun, menormalisasi, dan menganalisis data ke dalam bentuk tabel (DataFrame) |
| **gdown** | Mengunduh file JSON dari Google Drive jika data API disimpan secara lokal |
