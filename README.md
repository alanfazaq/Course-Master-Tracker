🚀 Frontend Course Tracker Pro

Aplikasi web responsif dan berkinerja tinggi untuk melacak progres belajar Front End Web Development. Project ini dibangun sebagai implementasi akhir dari silabus pelatihan fundamental Frontend, berfokus pada Vanilla JavaScript, Manipulasi DOM, Optimasi Performa Web, dan Aksesibilitas (WCAG).

🔗 Klik di sini untuk melihat Live Demo (GitHub Pages) (Ganti tanda '#' dengan link GitHub Pages Anda nanti)

✨ Fitur Utama

Real-time Progress Bar: Melacak persentase penyelesaian materi secara dinamis.

Manajemen Materi: Tambah materi baru dan tandai materi yang sudah selesai.

Smart Search (Filter): Mencari materi dengan cepat (dilengkapi dengan teknik Debounce untuk mencegah lag).

Sistem Rekomendasi: Fitur "Sarankan Topik Selanjutnya" untuk mencari modul pertama yang belum diselesaikan.

100% Responsif: Tampilan yang dioptimalkan untuk Desktop, Tablet (menggunakan CSS Grid), dan Mobile.

🛠️ Konsep & Teknologi yang Didemonstrasikan

Sesuai dengan silabus kursus, project ini mengimplementasikan konsep-konsep krusial berikut:

1. JavaScript Fundamentals & Control Flow

Menggunakan berbagai jenis loops sesuai dengan best practice dan efisiensi:

for loop: Untuk mengkalkulasi persentase progress bar.

while loop: Digunakan sebagai metode tercepat untuk membersihkan elemen DOM.

do...while loop: Untuk algoritma pencarian saran topik belajar.

2. DOM Manipulation & Events

Menghindari modifikasi HTML secara sembarangan dengan menggunakan event addEventListener.

Membuat, menghapus, dan memanipulasi elemen DOM (seperti styling progress-bar) murni menggunakan JavaScript.

3. Web Performance Optimization

DocumentFragment: Memasukkan banyak elemen HTML ke layar dalam satu waktu untuk mencegah Reflow/Repaint yang berlebihan pada browser, membuat proses render jauh lebih ringan.

Debounce: Diimplementasikan pada fitur pencarian (Search). Sistem akan menunda eksekusi pencarian selama 300ms saat user mengetik, sehingga tidak membebani memori browser.

4. Web Accessibility (A11y)

Semantic HTML: Menggunakan tag seperti <header>, <main>, <section>.

Keyboard Navigation: Indikator visual (garis dashed tebal) saat pengguna bernavigasi menggunakan tombol Tab. Manajemen focus dikembalikan ke input form setelah interaksi.

Screen Reader Support: Menggunakan atribut aria-live, aria-valuenow, aria-label, serta class .sr-only untuk memastikan pengguna disabilitas (Tunanetra) dapat memahami konteks aplikasi.
