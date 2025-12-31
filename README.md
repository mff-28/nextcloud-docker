# Nextcloud + PostgreSQL (Docker Compose)

Deployment **Nextcloud** menggunakan **Docker Compose** dengan database **PostgreSQL**, port custom **8050**, custom network, dan penyimpanan data persisten di `/mnt/sdd1/nextcloud`.

---

## 📦 Stack
- **Nextcloud** (Apache)
- **PostgreSQL 15**
- **Docker Compose v3.8**

---

## 📁 Struktur Direktori

```bash
/mnt/sdd1/nextcloud
├── app/    # Data aplikasi Nextcloud
├── db/     # Data database PostgreSQL
└── docker-compose.yml
