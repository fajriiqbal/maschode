# Template Website Sekolah Modern

Template website sekolah yang modern, responsif, dan mudah dikustomisasi menggunakan HTML5, CSS3, dan Tailwind CSS. Template ini dirancang khusus untuk lembaga pendidikan seperti SMA, SMK, MTs, atau pesantren.

## 🎯 Fitur Utama

### ✨ Desain & User Experience
- **Desain Modern**: Interface yang clean dan profesional
- **Responsif**: Optimal di semua device (desktop, tablet, mobile)
- **Animasi Smooth**: Transisi dan animasi yang halus
- **Loading Cepat**: Optimasi performa untuk loading yang cepat
- **SEO Friendly**: Struktur HTML yang SEO-optimized

### 🚀 Fungsionalitas
- **Navigation Sticky**: Menu navigasi yang tetap terlihat saat scroll
- **Mobile Menu**: Menu hamburger untuk perangkat mobile
- **Smooth Scrolling**: Scroll halus antar section
- **Contact Form**: Form kontak dengan validasi
- **Counter Animation**: Animasi counter untuk statistik
- **Modal System**: Sistem modal untuk konten popup
- **Notification System**: Sistem notifikasi untuk feedback user

### 📱 Responsif
- **Mobile First**: Dikembangkan dengan pendekatan mobile-first
- **Breakpoint Optimized**: Tampilan optimal di semua ukuran layar
- **Touch Friendly**: Interface yang ramah untuk touch device

## 🎨 Teknologi yang Digunakan

- **HTML5**: Struktur semantic yang modern
- **CSS3**: Styling advanced dengan fitur terbaru
- **Tailwind CSS**: Framework CSS utility-first
- **JavaScript ES6+**: Fungsionalitas interaktif modern
- **Font Awesome**: Icon set yang lengkap
- **Google Fonts (Inter)**: Typography yang modern dan readable

## 📁 Struktur File

```
school-website-template/
├── index.html          # Halaman utama
├── styles.css          # CSS custom tambahan
├── script.js           # JavaScript functionality
├── README.md           # Dokumentasi ini
└── assets/             # (opsional untuk gambar)
    ├── images/
    └── icons/
```

## 🛠️ Instalasi & Setup

### 1. Download Template
```bash
# Clone atau download file template
git clone [repository-url]
cd school-website-template
```

### 2. Buka File
- Buka `index.html` di browser favorit Anda
- Atau gunakan live server untuk development

### 3. Kustomisasi
- Edit konten di `index.html`
- Sesuaikan warna dan styling di `styles.css`
- Tambahkan fungsionalitas di `script.js`

## 🎨 Kustomisasi

### Mengubah Warna Tema
Edit variabel warna di bagian Tailwind config dalam `index.html`:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: {
                    50: '#eff6ff',
                    500: '#3b82f6',  // Warna utama
                    600: '#2563eb',
                    700: '#1d4ed8',
                }
            }
        }
    }
}
```

### Mengubah Font
Ganti font di bagian `<head>`:

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### Mengubah Konten
1. **Logo & Nama Sekolah**: Edit di bagian navigation
2. **Hero Section**: Ubah judul, deskripsi, dan gambar
3. **About Section**: Sesuaikan informasi sekolah
4. **Programs**: Tambah/edit program yang tersedia
5. **Contact Info**: Update informasi kontak

## 📋 Sections yang Tersedia

### 1. Navigation Bar
- Logo sekolah
- Menu navigasi
- Tombol CTA
- Mobile hamburger menu

### 2. Hero Section
- Judul utama dengan efek gradient
- Deskripsi sekolah
- Call-to-action buttons
- Statistik achievement overlay

### 3. Features Section
- Grid 6 fitur unggulan
- Icon dan deskripsi
- Hover effects

### 4. About Section
- Informasi sekolah
- Visi dan misi
- Statistik sekolah
- Image gallery

### 5. Programs Section
- Program studi yang tersedia
- Card layout dengan gambar
- Call-to-action per program

### 6. News Section
- Berita dan kegiatan terbaru
- Card layout dengan tanggal
- Thumbnail images

### 7. Contact Section
- Informasi kontak lengkap
- Form kontak dengan validasi
- Maps integration ready

### 8. Footer
- Links navigasi
- Social media icons
- Copyright information

## 🔧 Fitur JavaScript

### Validasi Form
```javascript
// Form akan otomatis divalidasi
// Email format validation
// Required field validation
// Success/error notifications
```

### Modal System
```javascript
// Buka modal
openModal('Judul Modal', 'Konten HTML');

// Modal akan otomatis close dengan ESC atau click outside
```

### Notification System
```javascript
// Tampilkan notifikasi
showNotification('Pesan berhasil!', 'success');
showNotification('Terjadi error!', 'error');
```

### Counter Animation
Tambahkan class `counter` pada elemen angka untuk animasi count-up otomatis.

## 📱 Browser Support

- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile browsers

## 🚀 Optimasi Performa

### 1. Image Optimization
- Gunakan format WebP untuk gambar modern
- Lazy loading untuk gambar
- Responsive images dengan srcset

### 2. CSS Optimization
- Tailwind CSS purged untuk production
- Critical CSS inlined
- Minifikasi CSS

### 3. JavaScript Optimization
- Async/defer loading
- Code splitting untuk fitur optional
- Debounced scroll events

## 🎯 SEO Features

- ✅ Semantic HTML5 structure
- ✅ Meta tags optimized
- ✅ Open Graph tags
- ✅ Schema.org markup ready
- ✅ Sitemap structure
- ✅ Fast loading speed

## 🔄 Maintenance

### Update Tailwind CSS
```html
<!-- Ganti URL CDN dengan versi terbaru -->
<script src="https://cdn.tailwindcss.com"></script>
```

### Update Font Awesome
```html
<!-- Ganti URL CDN dengan versi terbaru -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
```

## 🤝 Contributing

1. Fork repository
2. Buat feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push ke branch (`git push origin feature/amazing-feature`)
5. Buat Pull Request

## 📄 License

Template ini bebas digunakan untuk keperluan komersial maupun non-komersial.

## 🆘 Support

Jika mengalami masalah atau butuh bantuan:

1. Cek dokumentasi ini terlebih dahulu
2. Lihat issues yang sudah ada
3. Buat issue baru dengan detail yang jelas
4. Atau hubungi developer

## 🎓 Penggunaan untuk Berbagai Jenis Sekolah

Template ini dapat dengan mudah disesuaikan untuk:

### SMA/SMK
- Program Studi: IPA, IPS, Bahasa
- Ekstrakurikuler: OSIS, Pramuka, Olahraga
- Berita: Prestasi siswa, kegiatan sekolah

### MTs (Madrasah Tsanawiyah)
- Program: Tahfidz, Bahasa Arab, Umum
- Kegiatan: Pesantren kilat, kajian Islam
- Fasilitas: Mushola, perpustakaan

### Pesantren
- Program: Tahfidz Quran, Fiqh, Hadist
- Kegiatan: Pengajian, haflah
- Fasilitas: Asrama, masjid

## 🎨 Color Palette

### Primary Colors
- **Primary 50**: `#eff6ff` (Background light)
- **Primary 500**: `#3b82f6` (Main brand color)
- **Primary 600**: `#2563eb` (Hover states)
- **Primary 700**: `#1d4ed8` (Active states)

### Semantic Colors
- **Success**: `#10b981` (Green)
- **Warning**: `#f59e0b` (Yellow)
- **Error**: `#ef4444` (Red)
- **Info**: `#3b82f6` (Blue)

## 📐 Typography Scale

- **Heading 1**: `text-4xl lg:text-6xl` (36px-60px)
- **Heading 2**: `text-3xl lg:text-4xl` (30px-36px)
- **Heading 3**: `text-xl` (20px)
- **Body Large**: `text-xl` (20px)
- **Body**: `text-base` (16px)
- **Small**: `text-sm` (14px)

## 🎭 Animation Classes

### Fade Animations
- `.fade-in-up` - Fade in dari bawah
- `.slide-in-left` - Slide in dari kiri
- `.slide-in-right` - Slide in dari kanan

### Hover Effects
- `.card-hover` - Efek hover untuk card
- `.transform hover:scale-105` - Scale on hover
- `.hover:shadow-xl` - Shadow on hover

## 🔧 Advanced Customization

### Menambah Section Baru
```html
<section class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <!-- Konten section -->
    </div>
</section>
```

### Menambah Card Component
```html
<div class="bg-white rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300 transform hover:-translate-y-2 p-6">
    <!-- Konten card -->
</div>
```

### Custom Animation
```css
@keyframes customAnimation {
    0% { transform: translateX(-100%); opacity: 0; }
    100% { transform: translateX(0); opacity: 1; }
}

.custom-animate {
    animation: customAnimation 0.6s ease-out;
}
```

---

**Template Website Sekolah Modern** - Dibuat dengan ❤️ untuk kemajuan pendidikan Indonesia