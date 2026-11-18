# Estimasi Biaya Infrastruktur Cloud (v1)

## 1. Tujuan

Estimasi biaya ini dibuat untuk memperkirakan kebutuhan anggaran dalam pengujian tiga model layanan cloud, yaitu Virtual Machine (VM), Container, dan Function as a Service (FaaS).

Perkiraan biaya disusun sebelum implementasi dilakukan agar kelompok dapat memilih layanan yang sesuai dengan kebutuhan eksperimen dan anggaran yang tersedia.

## 2. Rencana Penggunaan Infrastruktur

Proyek direncanakan berjalan selama tiga minggu dengan menggunakan DCloud sebagai penyedia utama untuk layanan VM dan Container. Sementara itu, penyedia layanan FaaS masih dalam tahap penentuan.

| Layanan | Platform | Kebutuhan |
|---|---|---|
| Virtual Machine | DCloud VMware | Menjalankan API Python |
| Container | DCloud DKubes | Menjalankan API dalam container |
| FaaS | Belum ditentukan | Menjalankan fungsi komputasi yang sama |
| Load Testing | Grafana k6 | Menguji kinerja layanan |

## 3. Estimasi Biaya Awal

Berdasarkan konfigurasi yang telah dicoba pada portal DCloud, layanan VM dengan spesifikasi 1 vCPU, RAM 2 GB, dan penyimpanan 40 GB memiliki harga Rp465.000 per bulan atau Rp15.500 per hari.

Jika diasumsikan menggunakan tarif harian selama 21 hari, perkiraan biaya VM adalah:

Rp15.500 × 21 hari = Rp325.500.

Perhitungan ini merupakan estimasi awal. Jumlah tagihan sebenarnya mengikuti ketentuan pembayaran dan durasi penggunaan layanan.

| Komponen | Estimasi Biaya |
|---|---|
| VM DCloud VMware (21 hari) | Rp325.500, asumsi tarif harian |
| Container DKubes | Belum dikonfirmasi |
| FaaS | Belum ditentukan |
| Load Testing k6 lokal | Rp0 biaya layanan cloud |
| Biaya tambahan jaringan/penyimpanan | Belum dikonfirmasi |
| Total keseluruhan | Belum dapat ditentukan |

## 4. Rencana Penggunaan Free Trial

Kelompok telah mengajukan program DCloud XPlore 2026 yang menawarkan free trial selama tiga bulan.

Saat dokumen ini dibuat, pengajuan masih menunggu verifikasi. Oleh karena itu, pengurangan biaya dari program trial belum dimasukkan ke dalam perhitungan.

Biaya aktual akan dicatat setelah layanan berhasil diaktifkan dan digunakan.

## 5. Evaluasi Biaya

Setelah eksperimen selesai, kelompok akan membandingkan estimasi awal dengan biaya sebenarnya berdasarkan informasi tagihan atau penggunaan layanan.

Perbedaan biaya akan dijelaskan dengan mempertimbangkan durasi penggunaan, spesifikasi resource, diskon trial, dan biaya tambahan yang muncul.

## 6. Kesimpulan Sementara

Biaya VM sudah memiliki perkiraan awal berdasarkan harga yang muncul pada portal DCloud. Sementara itu, biaya Container dan FaaS belum dapat ditentukan karena masih menunggu kepastian layanan dan konfigurasi yang digunakan.

Dokumen ini akan diperbarui setelah seluruh lingkungan eksperimen ditetapkan.

## Referensi

- DCloud Pricing: https://dcloud.co.id/pricing.html
- DCloud XPlore 2026: https://dcloud.co.id/promo-dcloud-xplore-2026.html
- Dokumentasi DKubes: https://docs.dcloud.co.id/documentation/products/container/dkubes-dcloud/

Status: Draft v1 — 18 November 2026.
