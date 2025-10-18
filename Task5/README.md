# DevOps Setup Project

Proyek ini dibuat untuk mendemonstrasikan dasar-dasar DevOps, termasuk:
- Version control (Git & GitHub)
- CI/CD pipeline
- Containerization (Docker)
- Infrastructure as Code (Terraform)
- Monitoring & Logging (conceptual)


## Project Setup Instructions

1. **Clone repository**
   ```bash
   git clone https://github.com/SamAlino/99group-DevOps-internship/tree/main
2. Build Docker Image
4. Run using docker compose
5. Aplikasi akan berjalan di http://localhost

## Design Decisions
1. GitHub Actions digunakan untuk CI/CD karena mudah terintegrasi langsung dengan repository.
2. Docker memastikan aplikasi berjalan di lingkungan yang konsisten.
3. Terraform digunakan untuk provisioning environment secara otomatis (bonus task).
4. Prometheus dan Grafana direncanakan untuk monitoring di production.

## Future Improvements
Jika memiliki lebih banyak waktu, saya akan menambahkan:
1. Continuous Deployment ke AWS atau Google Cloud Run.
2. Pengujian otomatis (unit dan integration test).
3. Alerting otomatis dengan Slack/Email.
4. Log centralization dengan Loki atau ELK Stack.
5. Dokumentasi tambahan untuk setup di environment cloud.

##Author
Nama: Bonifasius Samuel
