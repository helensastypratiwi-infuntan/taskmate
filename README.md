# TaskMate – Week 1 (Expo Go + Expo Router, JavaScript)

Repositori ini berisi **starter praktikum** untuk aplikasi **TaskMate**.  
Mahasiswa diminta **membuat proyek Expo baru**, lalu **menyalin folder-file tertentu** dari paket starter agar bisa langsung dijalankan di **Expo Go**.

 Buat Project Expo

> Jalankan di terminal:

```bash
npx create-expo-app taskmate --template tabs@latest
cd taskmate
```
Apa saja yang harus dicopy

app/                    # halaman & navigasi tabs (Expo Router)
  _layout.jsx
  index.jsx
  add.jsx
  progress.jsx

src/                    # komponen & data
  components/TaskItem.jsx
  data/dummyTasks.js

README.md               # (opsional) penjelasan project

Catatan:

JANGAN menghapus file/folder lain yang dibuat otomatis oleh create-expo-app (mis. package.json, app.json, dsb).

jalankan 
```bash
npm start
```
pilih huruf yang sesuai


