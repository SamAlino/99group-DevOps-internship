# Monitoring & Logging Plan

## Tujuan
Monitoring digunakan untuk memastikan aplikasi berjalan dengan baik, mendeteksi error lebih cepat, dan melihat performa sistem.

## Tools yang Digunakan
- **Prometheus** → mengumpulkan metrik seperti CPU, memory, dan response time.  
- **Grafana** → menampilkan metrik dari Prometheus dalam bentuk dashboard.  
- **Loki** → menyimpan dan mencari log dari aplikasi.  

## Metrik Penting
- Response time (waktu respon API)
- Error rate (jumlah error)
- CPU & Memory usage
- Container health (jika pakai Docker)

## Contoh Konfigurasi Prometheus (sederhana)
```yaml
scrape_configs:
  - job_name: "my-app"
    static_configs:
      - targets: ["localhost:8000"]
