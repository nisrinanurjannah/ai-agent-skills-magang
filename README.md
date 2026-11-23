# AI Agent Skills: Otomasi Tugas Repetitif Magang

Repositori ini berisi kumpulan **AI Agent Skills** berbasis standar terbuka (`SKILL.md`) yang dirancang untuk mengotomatisasi pekerjaan administratif dan operasional berulang (repetitif) pada 5 studi kasus lokasi magang.

## Daftar Studi Kasus & AI Agent Skills

| No | Studi Kasus Magang | Nama Skill | Alur Kerja & Fokus Otomasi |
| :--- | :--- | :--- | :--- |
| **1** | Administrasi Perkantoran (Pemda) | `pemda-surat-admin` | Ekstraksi agenda surat masuk -> Rekomendasi disposisi -> Penyusunan draf surat dinas resmi. |
| **2** | Klinik Dokter (Registrasi & Anamnesa) | `klinik-triage-anamnesa` | Verifikasi identitas -> Anamnesa keluhan terstruktur -> Skrining *red flag* -> Ringkasan SOAP dokter. |
| **3** | Digital Marketing Agency | `agency-content-reporter` | Pemetaan pilar konten/data iklan -> Produksi *caption* atau kalkulasi metrik -> Rekomendasi optimasi. |
| **4** | Perusahaan Sawit (Bagian HRD) | `sawit-hr-screener` | Skrining & skoring CV pelamar kebun/pabrik -> Audit jatuh tempo kontrak PKWT & sertifikat K3. |
| **5** | Bank (Bagian Kredit) | `bank-credit-precheck` | Audit kelengkapan berkas -> Perhitungan rasio DSR -> Pemetaan analisis awal prinsip 5C. |

## Cara Penggunaan
1. Unduh atau salin folder `skills/` ke dalam direktori proyek AI Agent yang mendukung format `SKILL.md` (seperti Claude Code, Cursor, Windsurf, atau GitHub Copilot).
2. Panggil *skill* yang diinginkan di dalam *prompt* sesuai studi kasus pekerjaan yang sedang ditangani.
