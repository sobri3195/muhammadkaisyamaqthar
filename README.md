# Muhammad Kaisyam Aqthar — Legacy Journal

Website personal portfolio modern untuk mendokumentasikan perjalanan pertumbuhan, pendidikan, nilai, serta visi masa depan Kaisyam. Dibangun dengan **Vite, React, TypeScript, Tailwind CSS, Framer Motion,** dan **Lucide React**.

## Menjalankan proyek

```bash
npm install
npm run dev
```

Buka alamat yang ditampilkan Vite (biasanya `http://localhost:5173`). Untuk membuat production build:

```bash
npm run build
npm run preview
```

## Mengubah konten

Semua konten yang sering diperbarui dikelompokkan pada satu file: `src/data/kaisyamData.ts`.

- Ubah profil dasar di konstanta `profile`.
- Tambahkan fase pertumbuhan ke array `timeline`.
- Ubah nilai karakter di `values` dan jenjang pendidikan di `roadmap`.
- Tambahkan pencapaian ke `achievements`; kategori filter akan muncul otomatis.
- Perbarui galeri di `photos` dan jurnal ilustratif di `development`.

Area foto saat ini berupa placeholder desain agar aman digunakan sebelum foto keluarga ditambahkan. Ganti elemen placeholder pada komponen dengan tag `<img>` atau sumber aset lokal ketika foto sudah siap.

## Struktur

- `src/components/` — komponen UI reusable.
- `src/data/kaisyamData.ts` — pusat data konten yang mudah dikelola orang tua.
- `src/pages/Home.tsx` — susunan seluruh section halaman.
- `src/index.css` — token visual dan komponen Tailwind.

## Catatan

Nilai progress perkembangan adalah ilustrasi jurnal pribadi dan bukan penilaian medis atau psikologis. Tombol Download CV sengaja dinonaktifkan sampai CV siap diisi.
