---
layout: item
title: "Pengembangan"
date: 2018-05-16 16:25:06 +0700
comments: true
toc: true
cat: Dashboard Pimpinan
---

[![cover-manual-book-dashboard-pimpinan](../images/dashboard-pimpinan/pengembangan/cover-manual-book-dashboard-pimpinan.jpeg)](../images/dashboard-pimpinan/pengembangan/cover-manual-book-dashboard-pimpinan.jpeg)

Document manual book ini dibuat untuk memberikan panduan penggunaan aplikasi **Dashboard Pimpinan**, dimana Aplikasi Dashboar Pimpinan adalah aplikasi antar muka untuk monitoring dan mempermudah Pimpinan untuk melihat dan menilai kinerja SKPD (Satuan Kerja Perangkat Daerah). Perangkat lunak yang di butuhkan untuk pengujian aplikasi adalah Ubuntu 17 sebagai Operasi System. Sumber daya manusia untuk menggunakan aplikasi ini terutama dari Pimpinan dinas Provinsi Banten, penggunaan aplikasi ini terlebih dahulu diberikan pengenalan dan pelatihan yang cukup untuk menggunakan aplikasi *Dashboard Pimpinan*.

### 1. Struktur Menu
Adapun struktur menu pada aplikasi Dashboard Pimpinan adalah sebagai berikut:
#### 1.1 Menu Home

#### 1.2 Menu Dashboard
- **Kepegawaian**

#### 1.3 Menu Data Kepegawaian
- **List Pegawai**
- **List Pegawai KPO**
- **List Pegawai Esselon**
- **List Usia ASN**
- **List Pegawai Yang Akan Pensiun**

#### 1.4 **Menu Users**
- **Users List**
- **Role User**
- **User Profile**
- **Permissions**
- **Add new user**

Untuk memulai akses terhadap aplikasi **Dashboard Pimpinan**. Buka web browser (IE, Mozila Firefox atau yang lainnya) dengan menulis alamat url http://dashboard.bangunbanten.com kemudian tekan **Enter** pada tombol keyboard atau klik tombol **Go** pada browser. Akan muncul tampilan halaman login aplikasi dashboard seperti gambar dibawah ini.

[![tampilan-login-admin](../images/dashboard-pimpinan/pengembangan/tampilan-login-admin.png)](../images/dashboard-pimpinan/pengembangan/tampilan-login-admin.png)

**Gambar 1. Tampilan Login**

Masukkan User Id dan Password, Setelah di isi lengkap dan benar, klik button **Sign in** atau tekan tombol **Enter** pada keyboard. Sehingga akan menampilkan halaman utama sebagai berikut.

[![dashboard-home-awal](../images/dashboard-pimpinan/pengembangan/dashboard-home-awal.png)](../images/dashboard-pimpinan/pengembangan/dashboard-home-awal.png)
**Gambar 2. Tampilan Awal**

#### 2. Menu Home
Halaman muka (home) Dashboard Pimpinan Menampilkan 4 grafik:

- *Dashboard Kepegawaian*
- *Dashboard Kependudukan*
- *Dashboard Kesehatan*
- *Dashboard Kependidikan*

Seperti ditunjukan pada gambar berikut ini:

[![dashboard-home-awal](../images/dashboard-pimpinan/pengembangan/dashboard-home-awal.png)](../images/dashboard-pimpinan/pengembangan/dashboard-home-awal.png)
**Gambar 3. Halaman Utama (Home)**

Untuk menampilkan detail dashboard Kepegawaian dengan mengklik tombol **view more**.
maka akan ditampilkan detail grafik Jumlah pegawai, Kenaikan pangkat pegawai otomatis, Pegawai yang akan pensiun.Seperti ditunjukan pada gambar berikut ini:

[![dashboard-view-more-detail-jumlah-pegawai](../images/dashboard-pimpinan/pengembangan/view-more-detail-jumlah-pegawai.png)](../images/dashboard-pimpinan/pengembangan/view-more-detail-jumlah-pegawai.png)
**Gambar 4. Detail Prosentase dan Grafik Jumlah Pegawai**

[![dashboard-view-more-detail-kenaikan-pangkat-pegawai-otomatis](../images/dashboard-pimpinan/pengembangan/view-more-detail-kenaikan-pangkat-pegawai-otomatis.png)](../images/dashboard-pimpinan/pengembangan/view-more-detail-kenaikan-pangkat-pegawai-otomatis.png)
**Gambar 5. Detail Prosentase dan Grafik Kenaikan Pangkat Pegawai Otomatis**

[![dashboard-view-more-detail-pensiun-pegawai](../images/dashboard-pimpinan/pengembangan/view-more-detail-pensiun-pegawai.png)](../images/dashboard-pimpinan/pengembangan/view-more-detail-pensiun-pegawai.png)
**Gambar 6. Detail Prosentase dan Grafik Pensiun Pegawai**

#### 3. Menu Dashboard
Didalam menu dashboard ada beberapa cakupan diantaranya *Kepegawaian* (yang didalamnya mencakup jumlah pegawai, kenaikan pangkat pegawai otomatis, pegawai yang akan pensiun).dengan mengklik tombol kepegawaian sistem aplikasi akan menampilkan seperti ditujukan pada gambar dibawah ini:

[![view-more-detail-jumlah-pegawai](../images/dashboard-pimpinan/pengembangan/view-more-detail-jumlah-pegawai.png)](../images/dashboard-pimpinan/pengembangan/view-more-detail-jumlah-pegawai.png)
**Gambar 7.Prosentase dan Grafik Jumlah Pegawai**

[![view-more-detail-kenaikan-pangkat-pegawai-otomatis](../images/dashboard-pimpinan/pengembangan/view-more-detail-kenaikan-pangkat-pegawai-otomatis.png)](../images/dashboard-pimpinan/pengembangan/view-more-detail-kenaikan-pangkat-pegawai-otomatis.png)
**Gambar 8. Prosentase dan Grafik Kenaikan Pangkat Pegawai Otomatis**

[![view-more-detail-pensiun-pegawai](../images/dashboard-pimpinan/pengembangan/view-more-detail-pensiun-pegawai.png)](../images/dashboard-pimpinan/pengembangan/view-more-detail-pensiun-pegawai.png)
**Gambar 9. Prosentase dan Grafik Pensiun Pegawai**

#### 4. Menu Data Kepegawaian
Menu Data Kepegawaian adalah yang dipergunakan untuk Superadmin dan Admin, dimana bisa untuk Input, Hapus, Edit, Update, View data yang ada diseluruh Dinas Provinsi Banten. Didalam Menu Data Kepegawaian ada beberapa bagian menu, diantaranya adalah dengan tampilan gambar seperti dibawah ini:

**List Pegawai**
[![dashboard-list-tabel-pegawai](../images/dashboard-pimpinan/pengembangan/dashboard-list-tabel-pegawai.png)](../images/dashboard-pimpinan/pengembangan/dashboard-list-tabel-pegawai.png)
**Gambar 10. Data Jumlah Pegawai**

[![form-tabel-tambah-pegawai-admin](../images/dashboard-pimpinan/pengembangan/form-tabel-tambah-pegawai-admin.png)](../images/dashboard-pimpinan/pengembangan/form-tabel-tambah-pegawai-admin.png)
**Gambar 11. Form Tabel Tambah Jumlah Pegawai**

**List Pegawai KPO**
[![dashboard-list-tabel-pegawai-kenaikan-pangkat-otomatis](../images/dashboard-pimpinan/pengembangan/dashboard-list-tabel-pegawai-kenaikan-pangkat-otomatis.png)](../images/dashboard-pimpinan/pengembangan/dashboard-list-tabel-pegawai-kenaikan-pangkat-otomatis.png)
**Gambar 12. List Data Pegawai KPO**

[![form-tabel-tambah-pegawai-kenaikan-pangkat-otomatis-admin](../images/dashboard-pimpinan/pengembangan/form-tabel-tambah-pegawai-kenaikan-pangkat-otomatis-admin.png)](../images/dashboard-pimpinan/pengembangan/form-tabel-tambah-pegawai-kenaikan-pangkat-otomatis-admin)
**Gambar 13. Form Tabel Tambah Pegawai KPO**

**List Pegawai Esselon**
[![dashboard-list-tabel-jumlah-pegawai-esselon](../images/dashboard-pimpinan/pengembangan/dashboard-list-tabel-jumlah-pegawai-esselon.png)](../images/dashboard-pimpinan/pengembangan/dashboard-list-tabel-jumlah-pegawai-esselon.png)
**Gambar 14. List Data Jumlah Pegawai Esselon**

[![form-tabel-tambah-jumlah-pegawai-esselon-admin](../images/dashboard-pimpinan/pengembangan/form-tabel-tambah-jumlah-pegawai-esselon-admin.png)](../images/dashboard-pimpinan/pengembangan/form-tabel-tambah-jumlah-pegawai-esselon-admin.png)
**Gambar 15. Form Tabel Tambah Jumlah Pegawai Esselon**

**List Usia ASN**
[![dashboard-list-tabel-jumlah-usia-asn](../images/dashboard-pimpinan/pengembangan/dashboard-list-tabel-jumlah-usia-asn.png)](../images/dashboard-pimpinan/pengembangan/dashboard-list-tabel-jumlah-usia-asn.png)
**Gambar 16. List Data Jumlah Usia ASN**

[![form-tabel-tambah-Jumlah-usia-asn-admin](../images/dashboard-pimpinan/pengembangan/form-tabel-tambah-Jumlah-usia-asn-admin.png)](../images/dashboard-pimpinan/pengembangan/form-tabel-tambah-Jumlah-usia-asn-admin.png)
**Gambar 17. Form Tabel Tambah Jumlah Usia ASN**

**List Pegawai Yang Akan Pensiun**
[![dashboard-list-tabel-pegawai-yang-akan-pensiun](../images/dashboard-pimpinan/pengembangan/dashboard-list-tabel-pegawai-yang-akan-pensiun.png)](../images/dashboard-pimpinan/pengembangan/dashboard-list-tabel-pegawai-yang-akan-pensiun.png)
**Gambar 18. List Data Jumlah Pegawai Yang Akan Pensiun**

[![form-tabel-tambah-pegawai-yang-akan-pensiun-admin](../images/dashboard-pimpinan/pengembangan/form-tabel-tambah-pegawai-yang-akan-pensiun-admin.png)](../images/dashboard-pimpinan/pengembangan/form-tabel-tambah-pegawai-yang-akan-pensiun-admin.png)
**Gambar 19. Form Tabel Tambah Jumlah Pegawai Yang Akan Pensiun**

#### 5. Menu Users
Menu Users adalah tampilan aplikasi yang dipergunakan untuk Superadmin dan Admin, di mana bisa untuk Input, Hapus, Edit, Update, View data yang ada, dengan menekan atau klik tombol **create** akan tampil form tabel untuk penambahan data. Didalam menu users ada beberapa bagian menu, diantaranya adalah dengan tampilan gambar seperti dibawah ini:

**Users List**
[![users-list-tabel-admin](../images/dashboard-pimpinan/pengembangan/users-list-tabel-admin.png)](../images/dashboard-pimpinan/pengembangan/users-list-tabel-admin.png)
**Gambar 20. List Tabel Admin**

Klik tombol Create sistem aplikasi akan menampilakan gambar di bawah ini

[![add-user-admin](../images/dashboard-pimpinan/pengembangan/add-user-admin.png)](../images/dashboard-pimpinan/pengembangan/add-user-admin.png)
**Gambar 21. Form Tabel Add New User**

**Role User**
[![role-users-list-admin](../images/dashboard-pimpinan/pengembangan/role-users-list-admin.png)](../images/dashboard-pimpinan/pengembangan/role-users-list-admin.png)
**Gambar 22. List Lore User**

Klik tombol Create, sistem aplikasi akan menampilakan gambar di bawah ini.

[![form-tabel-add-role-user-admin](../images/dashboard-pimpinan/pengembangan/form-tabel-add-role-user-admin.png)](../images/dashboard-pimpinan/pengembangan/form-tabel-add-role-user-admin.png)
**Gambar 23. Form Tabel Add Role User**

**Permissions**
[![permissions-list-admin](../images/dashboard-pimpinan/pengembangan/permissions-list-admin.png)](../images/dashboard-pimpinan/pengembangan/permissions-list-admin.png)
**Gambar 24. List Permissions**

Klik tombol Create, sistem aplikasi akan menampilakan gambar di bawah ini.

[![form-tabel-add-permission-admin](../images/dashboard-pimpinan/pengembangan/form-tabel-add-permission-admin.png)](../images/dashboard-pimpinan/pengembangan/form-tabel-add-permission-admin.png)
**Gambar 25. Form Tabel Add Permissions**

**User Profile**
[![user-profile-admin-edit](../images/dashboard-pimpinan/pengembangan/user-profile-admin-edit.jpeg)](../images/dashboard-pimpinan/pengembangan/user-profile-admin-edit.jpeg)

**Gambar 26. Profile User**

**Add New User**
[![add-user-admin](../images/dashboard-pimpinan/pengembangan/add-user-admin.png)](../images/dashboard-pimpinan/pengembangan/add-user-admin.png)
**Gambar 27. Form Tabel Add New User**

