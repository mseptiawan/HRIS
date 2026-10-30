# SIMPEG - Sistem Informasi Kepegawaian

Sistem Informasi Kepegawaian (SIMPEG) adalah aplikasi berbasis web untuk membantu digitalisasi administrasi kepegawaian perusahaan. Sistem menyediakan pengelolaan data pegawai, kehadiran, cuti, lembur, dinas luar, hingga workflow persetujuan bertingkat (_multi-level approval_).

Proyek ini dikembangkan sebagai bagian dari tugas akhir dengan fokus pada arsitektur backend modular menggunakan Node.js, Express.js, MongoDB, dan Redis.

---

# Preview

## Dashboard

![Dashboard](docs/images/dashboard.png)

## Payroll

![Payroll](docs/images/payroll.png)

## Riwayat Daily Log

![Daily Log](docs/images/daily-log.png)

## Riwayat Kehadiran

![Attendance](docs/images/attendance-history.png)

## Riwayat Peminjaman Uang

![Loan History](docs/images/loan-history.png)

---

# Fitur

- Authentication berbasis Session
- Role-Based Access Control (RBAC)
- Manajemen Data Pegawai
- Manajemen Kehadiran
- Pengajuan Cuti
- Pengajuan Lembur
- Pengajuan Dinas Luar
- Multi-Level Approval Workflow
- Dashboard
- Notification
- Reporting
- Payroll _(Development)_
- Reward & Punishment _(Development)_

---

# Tech Stack

| Layer           | Technology             |
| --------------- | ---------------------- |
| Backend         | Node.js, Express.js    |
| Database        | MongoDB                |
| ODM             | Mongoose               |
| Cache           | Redis                  |
| Template Engine | EJS                    |
| CSS             | Tailwind CSS           |
| Authentication  | Session Authentication |
| Authorization   | RBAC                   |


---

# Arsitektur

```text
Client
   │
   ▼
Express Routes
   │
   ▼
Controllers
   │
   ▼
Services
   │
   ▼
Models
   │
   ▼
MongoDB

Redis
├── Session Store
└── Cache
```
# License

Proyek ini dikembangkan untuk tujuan akademik sebagai bagian dari penelitian tugas akhir.
