# Belajar GIMP (GNU Image Manipulation Program)

## 1. Pengenalan GIMP
GIMP adalah perangkat lunak pengolah gambar gratis dan open-source yang dapat digunakan untuk mengedit foto, membuat desain grafis, dan manipulasi gambar tingkat lanjut.

### 1.1 Instalasi GIMP
1. **Windows:** Unduh dari [https://www.gimp.org](https://www.gimp.org) dan ikuti instruksi pemasangan.
2. **Linux:** Bisa diinstal melalui terminal dengan perintah:
   ```bash
   sudo apt install gimp
   ```
3. **macOS:** Unduh versi terbaru dari situs resmi GIMP.

## 2. Antarmuka GIMP
- **Toolbox:** Berisi alat-alat untuk menggambar, seleksi, dan manipulasi gambar.
- **Image Window:** Area kerja utama tempat gambar ditampilkan.
- **Layers, Channels, Paths:** Panel untuk mengelola layer dan elemen gambar lainnya.
- **Brushes, Patterns, Gradients:** Berisi berbagai efek dan tekstur untuk desain.

## 3. Dasar-Dasar Penggunaan
### 3.1 Membuka dan Menyimpan Gambar
- **Membuka gambar:** `File > Open...`
- **Menyimpan gambar:** `File > Export As...` untuk format selain XCF (format asli GIMP)

### 3.2 Alat Dasar
- **Move Tool (M):** Memindahkan objek atau layer.
- **Selection Tools (R, E, F):** Untuk memilih bagian tertentu dari gambar.
- **Brush Tool (P):** Menggambar dengan berbagai jenis kuas.
- **Eraser Tool (Shift+E):** Menghapus bagian gambar.
- **Text Tool (T):** Menambahkan teks ke gambar.

## 4. Teknik Dasar Editing
### 4.1 Menggunakan Layer
- **Menambahkan Layer:** `Layer > New Layer...`
- **Mengubah Opacity:** Gunakan slider opacity pada panel layer.
- **Menggabungkan Layer:** `Layer > Merge Down`

### 4.2 Menggunakan Masking
- Tambahkan masking dengan klik kanan pada layer dan pilih `Add Layer Mask`.
- Gunakan kuas hitam untuk menyembunyikan dan putih untuk menampilkan.

### 4.3 Menghapus Background
1. Gunakan **Fuzzy Select Tool (U)** atau **Paths Tool (B)** untuk menyeleksi background.
2. Hapus dengan `Delete` atau gunakan Layer Mask untuk penghapusan non-destruktif.

