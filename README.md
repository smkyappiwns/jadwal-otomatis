🗓️ Aplikasi Generator Jadwal Mengajar Otomatis

Tanpa bentrok guru, ruang, dan kelas — 100% berbasis Google Sheets

✅ Login dengan Google (OAuth - GIS 2025)
✅ Tidak perlu database / server backend
✅ Data guru, mapel, ruang & kelas diambil dari Google Spreadsheet
✅ Jadwal otomatis dibuat tanpa tabrakan jam mengajar
✅ Spreadsheet hasil jadwal tersimpan otomatis di Google Drive
✅ UI modern (React + Tailwind) & responsif (HP / laptop)
✅ Bisa impor data melalui template Excel

🚀 Demo Online

🔗 [[https://smkyappiwns.github.io/jadwal-otomatis/)](https://smkyappiwns.github.io/jadwal-otomatis/))

📌 Fitur Utama
Fitur	Keterangan
🔐 Google Login	Autentikasi aman pakai Google Identity Services
📄 Google Sheets Storage	Semua data + output jadwal tersimpan di Drive pengguna
📥 Import Data	Bisa upload template Excel berisi daftar guru/mapel/ruang/kelas
🏫 Dropdown Auto Sync	Input form otomatis membaca data dari spreadsheet
⚡ Auto Scheduler	Algoritma membuat jadwal tanpa bentrok guru & ruang
🔁 Bisa Generate Ulang	Jadwal lama bisa dihapus & dibuat baru
📤 Export	Jadwal bisa diunduh sebagai Excel / PDF
🧠 Tanpa Database	Simpel, cukup spreadsheet sebagai backend
📱 Full Responsive	Bisa digunakan lewat HP guru / admin
🛠️ Teknologi
Teknologi	Fungsi
React + Vite	Frontend utama
TypeScript	Type safety
TailwindCSS	UI styling
Google Identity Services	Login OAuth terbaru (pengganti gapi)
Google Sheets API v4	CRUD data guru/mapel/kelas/ruang
Google Drive API	Simpan file jadwal otomatis
LocalStorage	Cache token & file ID
XLSX (SheetJS)	Import & export Excel
