# DBShy Bot

Bot Telegram + WhatsApp yang menggunakan token dari GitHub.

## Cara Setup

1. Buat file `token.json` di repo ini dengan format:
   ```json
   {
     "token": "TOKEN-BOT-TELEGRAM"
   }
   ```
   Atau jika lebih dari 1 token:
   ```json
   {
     "tokens": [
       "TOKEN1",
       "TOKEN2"
     ]
   }
   ```

2. Ambil link **Raw** file `token.json`:
   - Klik file `token.json`
   - Klik tombol **Raw**
   - Copy URL yang muncul di address bar

3. Tempel link itu ke variabel `GITHUB_TOKEN_LIST_URL` di file `akira.js`.

4. Jalankan bot:
   ```bash
   node akira.js
   ```

## Catatan Keamanan
- Jangan taruh token asli di repo public.
- Untuk keamanan, gunakan repo private atau file `.env`.
