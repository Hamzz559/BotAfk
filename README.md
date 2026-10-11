# CookisBot

Bot AFK Minecraft (Mineflayer) dengan dashboard web dan kontrol lewat Telegram.

## Install

```bash
npm install
node index.js
```

Pertama kali jalan, bot nanya data lu langsung di terminal:
token bot Telegram + ID Telegram (opsional), lalu `username`, `password`, `server`, `ip`.
Semua disimpan lokal di `settings.json` (nggak ikut ke GitHub).

Jalan berikutnya cukup Enter buat pakai data sebelumnya, atau ketik yang baru.
IP bisa pakai port, contoh `play.example.com:25565`.

## Perintah Telegram

`/akun` ganti akun, `/status`, `/web` (login dashboard), `/say <teks>`, `/stop`

## Catatan

Jangan bagikan `settings.json` ke siapa pun, isinya token dan password.


## Catatan build obfuscation
File JavaScript telah dipaketkan agar source lebih sulit dibaca sekilas. Ini bukan enkripsi kuat; siapa pun yang menjalankan program masih dapat mengekstrak source. Jangan menaruh token/password rahasia di file yang dibagikan.
