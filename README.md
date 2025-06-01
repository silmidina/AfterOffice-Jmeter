# Performance Testing with JMeter

Proyek ini berisi pengujian performa API Contact List App menggunakan Apache JMeter. Pengujian mencakup **Load Testing** dan **Stress Testing** dengan berbagai metode serta konfigurasi.

## Referensi

- **Dokumentasi API Contact List App:** [Klik di sini](https://documenter.getpostman.com/view/4012288/TzK2bEa8#bcd848eb-d7ae-4b73-9a0c-59eb2254017e)
- **Website Contact List App (UI):** [Klik di sini](https://thingking-tester-contact-list.herokuapp.com/)

## Fitur Pengujian

- Menggunakan 5 jenis request: `GET`, `POST`, `PUT`, `PATCH`, `DELETE`
- Implementasi **Bearer Token** untuk autentikasi

### Konfigurasi Elemen Tambahan

- CSV Data Set Config
- JSON Extractor
- Property File Reader (misalnya, membaca konfigurasi dari `Config.properties`)
- HTTP Request Default
- HTTP Header Manager
- HTTP Cookie Manager
- HTTP Cache Manager
- Logic Controller (minimal 2)
- Assertion dan Listener (minimal 2 listener)

## Hasil Pengujian

- Analisis waktu respons rata-rata, throughput, dan tingkat error
- Evaluasi kestabilan sistem terhadap beban tinggi

## Cara Menjalankan

1. Clone repository ini (pastikan source dari Contact List App sudah tersedia jika diperlukan)
2. Buka JMeter dan load file test plan
3. Jalankan pengujian dan analisis hasil

Untuk detail lebih lanjut, lihat laporan yang tersedia di Link Gdrive [Klik di sini](https://drive.google.com/drive/folders/1x_PWuBCQVAjW3OgOejVjUWDvatbg39n7).
