# 🛰️ LacakLokasi
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)
![Platform](https://img.shields.io/badge/platform-Windows%20|%20Linux-lightgrey)
![Made by](https://img.shields.io/badge/made%20by-muhammadluthfi24-black)

**LacakLokasi** adalah script Python sederhana untuk melacak dan menampilkan informasi lokasi berdasarkan alamat IP menggunakan API dari [`ip-api.com`](https://ip-api.com).

---

## 🚀 Fitur
- 🔍 Deteksi lokasi otomatis dari IP publik  
- 🌍 Menampilkan detail: Kota, Negara, ISP, Koordinat, Timezone  
- 📁 Export hasil ke **CSV** atau **XML**  
- 🧠 Tanpa registrasi atau API key — langsung jalan  

---

## ⚙️ Cara Pakai
```bash
git clone https://github.com/muhammadluthfi24/-lacaklokasi.git
cd lacaklokasi
python ipgeolocation.py -m
```
## Export ke CSV
```bash
python ipgeolocation.py -m -ec hasil.csv
```
## Export ke XML
```bash
python ipgeolocation.py -m -ex hasil.xml
```
⚠️ Catatan
Layanan ```bash ip-api.com ``` membatasi maksimal 150 request per menit.
Gunakan secara bijak agar IP kamu tidak diblokir otomatis.

📧 Author
🌐 github.com/muhammadluthfi24
