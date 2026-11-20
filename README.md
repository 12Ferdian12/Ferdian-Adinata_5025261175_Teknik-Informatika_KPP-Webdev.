# Ferdian Adinata — Personal Portfolio

Portfolio personal Ferdian Adinata, mahasiswa Teknik Informatika di Institut Teknologi Sepuluh Nopember. Website menampilkan profil, pengalaman, skill, pencapaian, project, dan kontak dalam desain dark navy–teal bergaya terminal.

## Live Preview

Buka `index.html` secara langsung di browser, atau deploy seluruh folder ke static hosting seperti GitHub Pages, Netlify, atau Vercel.

## Fitur

- Semantic HTML5.
- Native CSS3 tanpa framework.
- Responsive layout untuk desktop, tablet, dan mobile.
- Sticky navigation dengan backdrop blur.
- CSS-only mobile navigation.
- Smooth scrolling dan anchor offset agar heading tidak tertutup navbar.
- Focus state untuk keyboard navigation.
- Reduced-motion support melalui `prefers-reduced-motion`.
- Project showcase dengan repository GitHub, live demo, teknologi, dan screenshot.
- Tidak membutuhkan JavaScript, package manager, build process, atau backend.

## Isi Website

- **Home** — perkenalan singkat dan portrait.
- **About** — latar akademik, fokus teknis, dan status belajar.
- **Experience** — pengalaman R&D Manager, documentation staff, dan web developer.
- **Projects** — project personal, Kopi55, Comp Seek, Ferdian-A, dan SC Project.
- **Skills** — HTML, CSS, PHP, JavaScript, Python, Laravel, Tailwind CSS, Git, GitHub, VS Code, dan MySQL.
- **Achievements** — pencapaian kompetisi dan riset dari CV.
- **Contact** — email, GitHub, dan Instagram.

## Project Showcase

| Project | Deskripsi | Link |
| --- | --- | --- |
| Personal Web | Website personal untuk menampilkan karya dan skill. | [GitHub](https://github.com/12Ferdian12/Personal_Web) |
| Kopi55 | Website pembelajaran HTML, Vanilla CSS, dan PHP. | [GitHub](https://github.com/12Ferdian12/Kopi55) |
| Comp Seek | Platform pencarian kompetisi computer science dan paper call. | [GitHub](https://github.com/12Ferdian12/comp-seek) · [Demo](https://comp-seek.vercel.app) |
| Ferdian-A | Website personal versi sebelumnya. | [GitHub](https://github.com/12Ferdian12/Ferdian-A) |
| SC Project | Project web berbasis Next.js dan TypeScript dengan deployment Vercel. | [GitHub](https://github.com/12Ferdian12/sc-project) · [Demo](https://sc-project-12ferdian12.vercel.app/) |

Screenshot project berada di `assets/images/projects/`. Screenshot digunakan hanya untuk project yang sudah memiliki kecocokan konteks.

## Struktur Folder

```text
simple-portofolio/
├── index.html
├── README.md
├── css/
│   └── style.css
└── assets/
    └── images/
        ├── ferdian-portrait.jpeg
        ├── *.png / *.svg
        └── projects/
            ├── comp-seek.png
            ├── ferdian-a.png
            └── olativity.png
```

## Cara Menjalankan

Tidak ada instalasi dependency.

### Opsi 1 — Buka langsung

1. Buka folder project.
2. Klik dua kali `index.html`.
3. Website berjalan di browser.

### Opsi 2 — Static server lokal

Jika ingin menguji perilaku browser melalui HTTP, jalankan Python:

```bash
python -m http.server 8000
```

Lalu buka `http://localhost:8000`.

### Opsi 3 — Deploy

Upload seluruh folder project ke static hosting. Pastikan `index.html` berada di root deployment dan folder `css/` serta `assets/` ikut diunggah.

## Teknologi

- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS custom properties
- CSS media queries
- CSS transitions
- SVG dan raster images

## Prinsip Implementasi

- Konten identitas dan pencapaian bersumber dari website lama, repository GitHub, dan CV yang diberikan.
- Alamat rumah dan nomor telepon tidak ditampilkan.
- Tidak ada API key, token, password, atau credential di repository.
- Tidak ada external font, JavaScript, framework UI, atau dependency runtime.
- Repository dan live demo ditautkan hanya jika URL sudah diverifikasi.
- Deskripsi SC Project dibuat konservatif karena README repository memberikan detail project yang terbatas.

## Verifikasi

Pemeriksaan terakhir mencakup:

- HTML parse: PASS
- Anchor target: PASS
- Local asset reference: PASS
- Project screenshot files: PASS
- JavaScript portfolio files: `0`
- Horizontal overflow desktop/mobile: `0px`

## Kontak

- Email: `ferdianadinata07@gmail.com`
- GitHub: [@12Ferdian12](https://github.com/12Ferdian12)
- Instagram: [@f_rdi_n](https://www.instagram.com/f_rdi_n/)

## Lisensi

Belum ada lisensi open-source yang ditentukan. Minta izin sebelum menggunakan ulang konten personal, portrait, atau asset portfolio.
