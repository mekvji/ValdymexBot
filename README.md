<div align="center">
  <img src="https://raw.githubusercontent.com/mekvji/Pageme/refs/heads/main/1000452289-removebg-preview.png" width="200" alt="ValdyMex Logo">
  <h1>🤖 ValdyMex Studio</h1>
  <p><b>WhatsApp Bot Open Source - 100% Gratis & Edukatif</b></p>

  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Language-Node.js-green?style=for-the-badge" alt="NodeJS">
  <br><br>
  
  <a href="#-fitur-utama">Fitur Utama</a> • 
  <a href="#-instalasi">Instalasi</a> • 
  <a href="#-daftar-menu">Daftar Menu</a> • 
  <a href="#-media-sosial">Kontak</a>
</div>

<hr>

<h2>📢 Informasi Penting</h2>
<blockquote>
  <p><b>TIDAK UNTUK DIJUAL:</b> Script ini disediakan sepenuhnya secara GRATIS. Jika ada yang menjual script ini, itu adalah penipuan. Project ini dibuat untuk tujuan edukasi dan pengembangan komunitas.</p>
</blockquote>

<hr>

<h2 id="-fitur-utama">🌟 Fitur Unggulan</h2>
<ul>
  <li><b>Gemini AI Integrated:</b> Mampu menjawab berbagai pertanyaan secara otomatis.</li>
  <li><b>RPG Game System:</b> Fitur permainan lengkap (Berburu, Memancing, Inventory, dll).</li>
  <li><b>Management Tools:</b> Fitur Panel V2 (1GB - Unli) dan kontrol VPS.</li>
  <li><b>Media Downloader:</b> TikTok, YouTube, Mediafire, dan lain-lain.</li>
  <li><b>Automasi Group:</b> Anti-link, Welcome/Left, dan Tagall.</li>
</ul>

<hr>

<h2 id="-instalasi">🛠️ Panduan Instalasi Anti-Gagal (Termux)</h2>

<p>Ikuti langkah-langkah di bawah ini secara berurutan. Pastikan koneksi internet stabil selama proses instalasi.</p>

<h3>1. Persiapan Lingkungan Termux</h3>
<p>Salin dan tempel perintah ini untuk menginstal semua library sistem yang dibutuhkan:</p>
<pre>
<code>pkg update && pkg upgrade -y
pkg install nodejs git ffmpeg imagemagick python make g++ libwebp wget zip -y</code>
</pre>

<h3>2. Download Script (MediaFire)</h3>
<div align="center">
  <a href="https://www.mediafire.com/file/8xzq252d4tm62ir/valdymex.zip/file">
    <img src="https://img.shields.io/badge/Download_Script-MediaFire-blue?style=for-the-badge&logo=mediafire&logoColor=white" alt="Download MediaFire">
  </a>
</div>
<br>
<p>Jika kamu ingin mendownload langsung via terminal Termux, gunakan perintah ini:</p>
<pre>
<code># Download file zip
wget -O valdymex.zip "https://www.mediafire.com/file/8xzq252d4tm62ir/valdymex.zip"

# Unzip file
unzip valdymex.zip
cd bot</code>
</pre>

<h3>3. Instalasi Library Node.js</h3>
<p>Masuk ke folder script dan instal semua modul yang dibutuhkan:</p>
<pre>
<code>npm install</code>
</pre>

<h3>4. Konfigurasi Bot</h3>
<ol>
  <li>Dapatkan <b>API Key Gemini AI</b> di <a href="https://aistudio.google.com/app/apikey">Google AI Studio</a>.</li>
  <li>Buka file <code>setting.js</code>: <code>nano setting.js</code>.</li>
  <li>Masukkan API Key kamu pada bagian yang tersedia.</li>
  <li>Ubah nomor owner di <code>nano setting.js</code>.</li>
</ol>

<h3>5. Menjalankan Bot</h3>
<table>
  <tr>
    <th>Mode</th>
    <th>Perintah</th>
    <th>Keterangan</th>
  </tr>
  <tr>
    <td><b>Foreground</b></td>
    <td><code>node .</code></td>
    <td>Bot terlihat di layar (mati jika Termux ditutup).</td>
  </tr>
  <tr>
    <td><b>Background (PM2)</b></td>
    <td><code>npm start</code></td>
    <td>Bot tetap hidup di latar belakang.</td>
  </tr>
</table>

<hr>

<h2>⚠️ Solusi Error Umum</h2>

<details>
  <summary><b>Error saat 'npm install'</b></summary>
  <p>Pastikan kamu sudah menginstal build-tools dengan perintah: <code>pkg install python make g++</code>. Jika masih error, hapus folder node_modules dan coba lagi.</p>
</details>

<details>
  <summary><b>Pesan "Waiting for this message" di WhatsApp</b></summary>
  <p>Ini masalah enkripsi WhatsApp. Biarkan bot aktif selama beberapa jam dan pastikan sesi (folder auth) tidak sering dihapus.</p>
</details>

<hr>

<h2 id="-daftar-menu">📜 Daftar Menu Interaktif</h2>
<table width="100%">
  <tr>
    <th width="30%">Kategori</th>
    <th>Daftar Perintah (Commands)</th>
  </tr>
  <tr>
    <td><b>👑 Owner</b></td>
    <td>.setmenu, .addlimit, .addsewa, .ban, .unban, .setautobackup</td>
  </tr>
  <tr>
    <td><b>🧠 AI & Tools</b></td>
    <td>.ai, .gemini, .remini, .tohd, .obfus, .removebg, .brat</td>
  </tr>
  <tr>
    <td><b>⚔️ RPG Game</b></td>
    <td>.joinrpg, .inventory, .berburu, .memancing, .merampok, .pasar</td>
  </tr>
  <tr>
    <td><b>👥 Group</b></td>
    <td>.hidetag, .tagall, .antilinkgc, .kick, .promote, .setppgc</td>
  </tr>
  <tr>
    <td><b>📥 Downloader</b></td>
    <td>.tiktok, .play, .ytmp3, .ytmp4, .mediafire, .pstore</td>
  </tr>
  <tr>
    <td><b>☁️ Panel/VPS</b></td>
    <td>.1gb-v2, .5gb-v2, .unli-v2, .listpanel, .restartvps</td>
  </tr>
  <tr>
    <td><b>🎨 Maker</b></td>
    <td>.sticker, .qc, .smeme, .ephoto, .wm</td>
  </tr>
</table>

<hr>

<h2 id="-media-sosial">🌐 Media Sosial & Kontak</h2>
<div align="center">
  <a href="https://instagram.com/@jepara.allstar">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="IG">
  </a>
  <a href="https://youtube.com/@kajevc?si=5hN5u5k6RkDUOSgx">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YT">
  </a>
  <a href="https://wa.me/62882020750208">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WA">
  </a>
</div>

<br>

<div align="center">
  <p>Dibuat dengan ❤️ oleh <b>ValdyMexStudio</b></p>
  <img src="https://view-counter.api.fnkr.net/count.png?id=valdymex-repo&color=green" alt="Views">
</div>
