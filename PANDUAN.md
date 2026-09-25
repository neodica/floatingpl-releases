# Panduan Pemakaian FloatingPL

**FloatingPL** adalah widget melayang (selalu di atas) untuk MetaTrader 5 yang
menampilkan profit/loss berjalan (floating P/L) semua posisi sekaligus, harga,
equity, dan bisa mengelola posisi secara otomatis.

> **Aktivasi / beli kode:** ndr_dc@yahoo.com
> **Dukungan (support):** neo_dica@yahoo.co.id

---

## 1. Aktivasi

1. Jalankan **FloatingPL.exe**.
2. Pada layar aktivasi, masukkan **kode lisensi** yang Anda terima → klik **Aktifkan**.
3. Setelah berhasil, widget langsung terbuka. Aktivasi tidak perlu diulang untuk aplikasi yang sama.

**Catatan penting:**
- **1 kode = 1 aplikasi** (1 terminal/akun MT5). Untuk memantau **beberapa akun MT5**, Anda butuh **beberapa kode** (1 akun = 1 kode).
- **Tidak bisa pindah PC.** Kode yang sudah diaktivasi terkunci ke PC tersebut; kode yang sama tidak bisa dipakai di PC lain.
- Belum punya kode? Aplikasi memberi **masa coba (trial) 1 hari** otomatis saat pertama dijalankan.
- Jika Anda **install ulang / pindah folder MT5** dan aplikasi meminta aktivasi lagi, hubungi **support** untuk **reset** kode (masa aktif tetap).

---

## 2. Menghubungkan ke MetaTrader 5

1. Pastikan **MetaTrader 5 sudah terbuka dan login** ke akun Anda.
2. Aktifkan **AutoTrading** di MT5 (tombol di toolbar, atau tekan **Ctrl+E**) — wajib agar fitur otomatis bisa mengirim order.
3. Jika diminta, pilih file **terminal64.exe** dari folder MT5 yang ingin dipantau.

Jika widget menampilkan "⚠ MT5 tidak terhubung", buka/login MT5 lalu tunggu beberapa detik.

---

## 3. Membaca Tampilan

- **Angka besar** = floating P/L (total profit/rugi berjalan). Hijau = untung, merah = rugi.
- **Baris harga** = simbol utama + harga terkini (mis. XAUUSD).
- **Baris berputar** (ganti tiap ~4 detik): Equity ↔ Margin, dan posisi ↔ Balance.
- **Baris info** (berputar): RSI/Trend/Sesi + hitung mundur candle → P/L hari ini → status koneksi.
- **1 jam** = P/L 1 jam terakhir. **Today** = P/L, jumlah trade, dan % win hari ini.

---

## 4. Tombol & Menu

- **Geser widget:** tahan klik kiri lalu seret.
- **AUTO** (judul): master switch semua fitur otomatis (ON/OFF sekaligus).
- **Algo ON/OFF:** status AutoTrading MT5 (Ctrl+E).
- **+ / − :** perbesar / perkecil / ciutkan panel.
- **× :** tutup widget.
- **Klik kanan** membuka menu: ganti pair, SL+ sekarang, **Cek update**, **About / Versi**, dll.

---

## 5. Fitur Otomatis

| Fitur | Fungsi |
|---|---|
| **Auto Entry** | Membuka entry pemulihan saat floating minus (maks 1 aktif, ada jeda/cooldown). |
| **Auto Koreksi** | Scalping koreksi melawan tren (maks 3), keluar lewat Auto SL+. |
| **Auto SL+** | Trailing: mengunci profit posisi yang sudah untung. |
| **Auto CutLoss** | Menutup semua posisi bila rugi mencapai persentase yang diatur. |
| **Break-even Rescue** | Bila sudah 2+ posisi minus lalu harga berbalik, otomatis menutup semua saat kembali impas (0) — tanpa perlu Stop Loss. |

Semua fitur hanya berjalan jika **AutoTrading MT5 ON**.

---

## 6. Ganti Pair

Klik kanan → pilih pair (mis. XAUUSD, EURUSD, BTCUSD) → konfirmasi.
Ukuran lot otomatis menyesuaikan karakter pair yang dipilih.

---

## 7. Beberapa Akun / Banyak MT5 dalam 1 PC

- Anda bisa memantau **beberapa akun MT5** sekaligus di satu PC dengan menjalankan **beberapa widget** — **masing-masing memakai kodenya sendiri** (1 akun/terminal = 1 kode).
- **Jangan menjalankan beberapa widget secara bersamaan** — beri **jeda ±10 detik** antar widget, agar tiap widget sempat tersambung ke MT5-nya (kalau berbarengan, salah satu bisa gagal konek).
- Disarankan memakai **launcher berjeda** (file .vbs) agar otomatis.

---

## 8. Update Aplikasi

Klik kanan → **Cek update**. Jika ada versi baru, aplikasi akan mengunduh dan me-restart sendiri.
Update tidak pernah otomatis tanpa persetujuan Anda.

---

## 9. Keamanan Lisensi

- **1 kode = 1 aplikasi** dan **terkunci ke 1 PC**. Menggandakan file .exe **tidak** menambah lisensi.
- Jangan menyebarkan kode — kode yang sudah aktif akan ditolak bila dipakai di aplikasi/PC lain.
- Pindah PC atau install ulang MT5? Hubungi **support** untuk **reset** ikatan (sisa masa aktif tetap).

---

## 10. Kontak

- **Aktivasi / beli kode:** ndr_dc@yahoo.com
- **Dukungan (kendala/pertanyaan):** neo_dica@yahoo.co.id
