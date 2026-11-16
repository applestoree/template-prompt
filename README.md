# Visual Prompt Template

Template dasar untuk menyusun prompt visual produk Apple secara terstruktur.

## Prompt Variables

```text
[subject]:

[action]:

[background]:

[composition]:

[layout]:

[visual]:

[lighting]:

[typography]:

[quality]:

[ratio]:
```

## Variable Guide

| Variable | Fungsi |
|---|---|
| `[subject]` | **Nama produk Apple yang menjadi subjek utama visual.** Isi dengan nama produk/model, misalnya `iPhone 17 Pro Max`, `iPad Pro 13-inch (M5)`, atau `MacBook Air 15-inch (M4)`. Variable ini hanya berisi nama produk, bukan deskripsi visual atau instruksi gambar. |
| `[action]` | Menentukan aktivitas, posisi, atau interaksi produk dengan lingkungan atau elemen pendukung. |
| `[background]` | Menentukan latar tempat, lingkungan, dan elemen pendukung. |
| `[composition]` | Mengatur framing, sudut pandang, perspektif, dan penempatan produk. |
| `[layout]` | Mengatur susunan elemen visual dan ruang kosong dalam desain. |
| `[visual]` | Menentukan arah seni, gaya visual, dan karakter tampilan. |
| `[lighting]` | Menentukan sumber, arah, intensitas, dan karakter pencahayaan. |
| `[typography]` | Mengatur teks, hierarki tipografi, dan penempatannya; gunakan bila diperlukan. |
| `[quality]` | Menentukan detail, ketajaman, kualitas render, dan standar hasil akhir. |
| `[ratio]` | Menentukan rasio aspek atau format keluaran gambar. |

## Subject Rules

- `[subject]` hanya berisi nama produk Apple.
- Gunakan nama model yang spesifik jika tersedia.
- Jangan memasukkan deskripsi bentuk, warna, material, posisi, aksi, atau gaya visual ke dalam `[subject]`.
- Detail visual produk dan instruksi penampilannya ditentukan melalui variable lain atau instruksi Prompt Engine, bukan dengan memperluas isi `[subject]`.

## Usage

1. Isi `[subject]` dengan nama produk Apple yang akan ditampilkan.
2. Isi variable lainnya sesuai kebutuhan visual.
3. Pertahankan nama variable agar konsisten saat digunakan oleh Prompt Engine.
4. Hapus atau kosongkan variable yang tidak relevan untuk kebutuhan tertentu.
5. Gabungkan seluruh instruksi menjadi satu prompt final sebelum dikirim ke Image Generator.
