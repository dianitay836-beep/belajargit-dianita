Berikut adalah jawaban untuk bagian **Refleksi** pada LKPD 3:

1. **Mengapa branch diperlukan?**
* Branch diperlukan untuk **mengisolasi (memisahkan) proses pengembangan** fitur baru, perbaikan bug, atau eksperimen. Dengan branch, perubahan kode dilakukan di area kerja terpisah sehingga tidak mengganggu kode utama (`main`) yang sudah stabil.


2. **Apa keuntungan bekerja pada branch dibanding langsung di main?**
* **Keamanan Kode (Aman dari Error):** Jika terjadi kesalahan atau bug saat pembuatan fitur baru, proyek utama di branch `main` tidak akan rusak atau terpengaruh.
* **Memudahkan Kolaborasi Tim:** Beberapa pengembang (*developer*) bisa mengerjakan fitur yang berbeda-beda di waktu bersamaan tanpa saling menimpa (*overwrite*) program milik anggota tim lain.
* **Proses Review Lebih Terkontrol:** Fitur baru bisa diuji dan diperiksa terlebih dahulu sebelum digabungkan (*merge*) ke branch utama.


3. **Kapan sebaiknya membuat branch baru?**
* Saat akan **menambahkan fitur baru** (misalnya: membuat halaman profil, fitur *login*, atau keranjang belanja).
* Saat ingin **memperbaiki kesalahan/bug** (*bug fixing* atau *hotfix*).
* Saat ingin **melakukan eksperimen** atau mencoba teknologi baru tanpa risiko merusak proyek yang sudah ada.
