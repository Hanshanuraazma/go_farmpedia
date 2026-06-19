# Farmpedia - eCommerce Website

Website eCommerce yang fully responsive dengan kompatibilitas maksimal di semua perangkat mobile, dibangun menggunakan HTML, CSS, dan JavaScript.

## Demo

![Anon Desktop Demo](./website-demo-image/desktop.png "Desktop Demo")
![Anon Mobile Demo](./website-demo-image/mobile.png "Mobile Demo")

## Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript (Vanilla)
- Ionicons untuk ikon
- Google Fonts (Poppins)

## Instalasi Lokal

Untuk menginstall **Farmpedia** di komputer lokal:

```bash
git clone https://github.com/Hanshanuraazma/go_farmpedia.git
cd go_farmpedia
```

Kemudian buka `index.html` di browser Anda.

## Deploy ke Vercel

### Langkah 1: Push ke GitHub (Sudah Selesai ✓)
Repository ini sudah terhubung dengan GitHub.

### Langkah 2: Deploy ke Vercel

#### Opsi A: Deploy Otomatis dengan Button
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Hanshanuraazma/go_farmpedia)

#### Opsi B: Deploy Manual
1. Kunjungi [Vercel](https://vercel.com)
2. Login dengan akun GitHub Anda
3. Klik "Add New Project"
4. Pilih repository `Hanshanuraazma/go_farmpedia`
5. Framework Preset: **Other** (atau biarkan auto-detect)
6. Root Directory: `./` (default)
7. Klik **Deploy**

### Langkah 3: Tunggu Build Selesai
Vercel akan otomatis:
- Build dan deploy website
- Generate URL production (misalnya: `your-project.vercel.app`)
- Setup CDN global untuk performa maksimal

### Troubleshooting

Jika CSS tidak muncul:
1. Buka Vercel Dashboard
2. Pilih project Anda
3. Klik tab "Deployments"
4. Klik "Redeploy" pada deployment terbaru
5. Centang "Use existing Build Cache" = OFF (untuk force rebuild)
6. Klik "Redeploy"

Jika masih bermasalah, cek:
- Developer Console (F12) untuk error 404 atau CORS
- Pastikan path file CSS dan JS benar
- Vercel Log untuk error detail

## Struktur Project

```
go_farmpedia/
├── assets/
│   ├── css/
│   │   ├── style-prefix.css    # CSS utama
│   │   └── style.css           # CSS alternatif
│   ├── images/                  # Semua gambar
│   │   ├── icons/
│   │   ├── logo/
│   │   ├── products/
│   │   └── ...
│   └── js/
│       └── script.js            # JavaScript utama
├── website-demo-image/          # Screenshot demo
├── index.html                   # File HTML utama
├── vercel.json                  # Konfigurasi Vercel
└── README.md
```

## Fitur

- ✅ Fully Responsive Design
- ✅ Mobile-First Approach
- ✅ Product Grid & List View
- ✅ Modal Newsletter Subscribe
- ✅ Toast Notifications
- ✅ Category Navigation
- ✅ Product Filtering
- ✅ Mobile Navigation Menu
- ✅ Search Functionality
- ✅ Shopping Cart UI

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile Browsers (iOS Safari, Chrome Mobile)

## License

Project ini **bebas digunakan** dan tidak memiliki lisensi khusus.

## Kontribusi

Kontribusi sangat diterima! Silakan fork repository dan buat pull request.

## Link

- 🌐 **Repository**: https://github.com/Hanshanuraazma/go_farmpedia
- 🚀 **Live Demo**: (akan tersedia setelah deploy ke Vercel)

---

Dibuat dengan ❤️ untuk pembelajaran dan pengembangan
