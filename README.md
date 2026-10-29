# ai-caregiver-assistant
Prototype of AI Caregiver Assistant for Stroke Patients — IPPL Project.

# 🧠 AI Caregiver Assistant for Stroke Patients

> **Prototype of AI Caregiver Assistant for Stroke Patients** — Tugas Mata Kuliah Implementasi Perangkat Lunak (IPPL).

## 📖 Deskripsi Proyek
AI Caregiver Assistant adalah platform berbasis web yang dirancang untuk mendigitalkan proses pendampingan pasien stroke. Sistem ini memfasilitasi kolaborasi antara manajemen (President & Coordinator), tenaga pendamping (Caregiver), dan Admin untuk memastikan kualitas perawatan pasien stroke tetap optimal melalui bantuan *Artificial Intelligence* (AI).

## ✨ Fitur Utama

Sistem ini memiliki 4 Aktor utama dengan hak akses dan fitur masing-masing:

### 1. 👑 President (Top Management)
*   **Construction Board**: Dashboard eksekutif untuk memantau metrik tingkat tinggi (total pasien aktif, statistik performa, dan laporan umum sistem).

### 2. 📋 Coordinator (Manajemen Operasional)
*   **Kelola Member & Caregiver**: Mengelola pendaftaran dan penugasan (assignment) caregiver ke pasien.
*   **Kelola Patient Records & Rumah Sakit**: Manajemen data rekam medis pasien dan integrasi data rumah sakit terkait.
*   **Kelola Scheduling & Meeting**: Mengatur jadwal kunjungan/terapi pasien serta jadwal koordinasi tim.
*   **Kelola Logs & Notifikasi Jatuh Tempo**: Memantau *audit trail* (log aktivitas) sistem dan mengatur *reminder* (notifikasi).
*   **Kelola Obat**: Manajemen database obat-obatan pasien.
*   **Kelola AI Model & AI Bahasa Indonesia**: Konfigurasi *persona* AI dan *knowledge base* dalam bahasa Indonesia agar relevan dengan pengguna.

### 3. 🧑‍⚕️ Caregiver (Pendamping Lapangan)
*   **Login & Logout**: Autentikasi ke dalam sistem.
*   **Kelola Patient**: Melihat profil, riwayat medis, dan kondisi terkini pasien yang didampingi.
*   **Kelola AI Assistant**: Mengatur pengingat jadwal minum obat, jadwal terapi, dan berinteraksi dengan AI untuk saran perawatan.
*   **Notifikasi Jadwal**: Menerima *reminder* terkait jadwal pasien.
*   **Upload Obat/Terapi**: Mengunggah data terkait obat atau terapi baru.
*   **Logs**: Mencatat aktivitas harian pendampingan.

### 4. 🛡️ Admin (Backoffice)
*   **Login & Logout**: Autentikasi khusus admin.
*   **Kelola Pasien & Rumah Sakit**: Verifikasi data pendaftaran pasien.
*   **Kelola Pendaftaran Caregiver**: Memvalidasi akun caregiver (memastikan *credential* valid).
*   **Logs**: Memantau log sistem untuk keamanan (*security*).

## 🛠️ Teknologi yang Digunakan
- **Frontend**: HTML5, CSS3, Vanilla JavaScript (Web Speech API untuk *Voice Input*).
- **Backend**: PHP Native (REST API sederhana) *(Jika menggunakan XAMPP)* / Google Apps Script.
- **Database**: MySQL.
- **AI Engine**: Groq API (Model Llama 3) sebagai *Large Language Model* untuk Chat Assistant.

## 🚀 Status Pengembangan (Roadmap)
- [] Desain UI/UX & Frontend (Halaman Caregiver & AI Chat).
- [] Prototipe AI Chat Assistant (Integrasi Groq/LLM).
- [] Sistem Autentikasi (Login, Register, Lupa Password).
- [] Implementasi Backend PHP & Database MySQL (Dalam Proses).
- [] Implementasi Hak Akses (Role-Based Access Control) untuk President, Coordinator, dan Admin.

## 👨‍💻 Pengembang
- **Naila Kalsum - 11241069** - *Frontend & Backend Developer*

## ⚠️ Disclaimer
Proyek ini dibuat untuk keperluan **akademik/prototipe**. Segala bentuk jawaban dari AI bersifat **edukatif** dan tidak dapat dijadikan sebagai diagnosis medis resmi. Selalu konsultasikan kondisi pasien kepada dokter atau tenaga kesehatan profesional.
