# Prompt Variables

Dokumentasi variable yang digunakan dalam template prompt visual produk Apple.

## 1. `[products]`

**Fungsi:** Menentukan nama produk Apple yang menjadi subjek utama visual.

**Format value:** Nama produk dan model.

**Contoh:**
- `iPhone 17 Pro Max`
- `iPad Pro 13-inch (M5)`
- `MacBook Air 15-inch (M4)`
- `Apple Watch Ultra 3`
- `AirPods Pro 3`

**Aturan:**
- Hanya berisi nama produk Apple.
- Gunakan nama model spesifik jika tersedia.
- Jangan memasukkan deskripsi bentuk, warna, material, posisi, aksi, atau gaya visual.

## 2. `[action]`

**Fungsi:** Menentukan aktivitas, posisi, atau interaksi produk dengan lingkungan maupun elemen pendukung.

**Contoh:**
- Product floating in mid-air
- Product standing upright
- Product placed on a surface
- Multiple product devices arranged together

## 3. `[background]`

**Fungsi:** Menentukan latar tempat, lingkungan, dan elemen pendukung di belakang atau sekitar produk.

**Contoh:**
- Minimalist studio background
- Soft gradient background
- Modern workspace
- Abstract architectural environment

## 4. `[composition]`

**Fungsi:** Mengatur framing, sudut pandang, perspektif, jarak kamera, dan penempatan produk dalam frame.

**Contoh:**
- Front-facing product shot
- Three-quarter view
- Close-up detail shot
- Wide shot with negative space

## 5. `[layout]`

**Fungsi:** Mengatur susunan dan hierarki elemen visual, termasuk area produk, teks, elemen pendukung, dan ruang kosong.

**Contoh:**
- Centered hero product layout
- Asymmetric editorial layout
- Split composition
- Product with text area on the side

## 6. `[visual]`

**Fungsi:** Menentukan arah seni, gaya visual, dan karakter tampilan keseluruhan.

**Contoh:**
- Minimalist premium
- Photorealistic product advertising
- Clean editorial style
- Futuristic technology aesthetic

## 7. `[lighting]`

**Fungsi:** Menentukan sumber, arah, intensitas, warna, dan karakter pencahayaan.

**Contoh:**
- Soft studio lighting
- Dramatic side lighting
- Natural window light
- Subtle rim lighting

## 8. `[typography]`

**Fungsi:** Mengatur penggunaan teks dalam visual, termasuk jenis huruf, hierarki, ukuran relatif, alignment, dan penempatan.

**Contoh:**
- Bold headline with clean sans-serif typography
- Minimal text hierarchy
- Product name placed above the product
- No typography

**Catatan:** Gunakan sesuai kebutuhan konten. Jika tidak diperlukan, variable dapat dikosongkan.

## 9. `[quality]`

**Fungsi:** Menentukan standar kualitas hasil gambar, tingkat detail, ketajaman, dan kualitas render.

**Contoh:**
- High-detail photorealistic rendering
- Sharp product details
- Clean edges and realistic materials
- Professional commercial image quality

## 10. `[ratio]`

**Fungsi:** Menentukan rasio aspek atau format keluaran gambar.

**Contoh:**
- `1:1`
- `4:5`
- `9:16`
- `16:9`

---

## Variable Usage Rules

1. Pertahankan nama variable persis seperti yang ditentukan.
2. `[products]` hanya berisi nama produk Apple.
3. Setiap variable memiliki fungsi berbeda; hindari mengulang instruksi yang sama di beberapa variable.
4. Isi variable berdasarkan kebutuhan visual. Variable yang tidak relevan dapat dikosongkan.
5. Jangan memindahkan instruksi dari satu variable ke variable lain tanpa alasan fungsional.
6. Gabungkan value variable menjadi prompt final yang koheren sebelum dikirim ke Image Generator.

## Variable List

```text
[products]:

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
