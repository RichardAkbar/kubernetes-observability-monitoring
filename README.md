# Kubernetes Observability & Monitoring Platform

## 1. Gambaran Umum Project

### Tujuan Project

Membangun platform observability dan monitoring pada Kubernetes untuk centralized logging, metrics monitoring, visualisasi, dan troubleshooting.

## 2. Teknologi yang Digunakan

- Kubernetes
- Helm
- Elasticsearch
- Logstash
- Fluent Bit
- Kibana
- Prometheus
- Node Exporter
- Kube State Metrics
- Grafana
- GitHub

## 3. Arsitektur Sistem

### 3.1 Centralized Logging

Kubernetes Workloads → Fluent Bit → Logstash → Elasticsearch → Kibana

### 3.2 Metrics Monitoring

Kubernetes Cluster → Metrics Exporters → Prometheus → Grafana

## 4. Persiapan Environment

### 4.1 Playground

KodeKloud Kubernetes Multi-Node Playground.

### 4.2 Informasi Infrastruktur

| Komponen | Informasi |
|---|---|
| Control Plane | controlplane |
| Worker Nodes | node01, node02 |
| Jumlah Node | 3 |
| Kubernetes | v1.37.0 |
| Container Runtime | containerd 2.2.3 |
| Operating System | Ubuntu 22.04.5 LTS |
| Helm | v3.22.1 |
| CPU per Node | 16 |
| Memory Allocatable | 64756760Ki per node |
| StorageClass | Belum tersedia |
| PersistentVolume | Belum tersedia |

### 4.3 Validasi Environment

- [x] Semua node Ready.
- [x] Pod kube-system Running.
- [x] Helm tersedia.
- [x] CPU dan memory berhasil diperiksa.
- [x] StorageClass dan PersistentVolume diperiksa.
- [ ] Screenshot evidence dilengkapi.

## 5. Tahapan Implementasi

### Checkpoint 01 – Repository & Environment Preparation

**Aktivitas:** Membuat repository, struktur direktori, dan memvalidasi cluster Kubernetes.

**Hasil Implementasi:** Repository GitHub tersedia dan cluster memiliki tiga node Ready.

**Bukti Pengujian:**
- screenshots/phase-01/01-kubernetes-cluster-validation.png
- screenshots/phase-01/02-infrastructure-resource-validation.png

**Status:** Validasi selesai, screenshot menunggu dilengkapi.

### Checkpoint 02 – ELK Stack Exploration

**Aktivitas:** Belum dilaksanakan.

**Hasil Implementasi:** Menunggu eksplorasi.

**Bukti Pengujian:** Menunggu pengujian.

**Status:** Belum dimulai.

### Checkpoint 03 – Centralized Logging Deployment

**Aktivitas:** Belum dilaksanakan.

**Hasil Implementasi:** Menunggu deployment.

**Bukti Pengujian:** Menunggu pengujian.

**Status:** Belum dimulai.

### Checkpoint 04 – Prometheus Metrics Collection

**Aktivitas:** Belum dilaksanakan.

**Hasil Implementasi:** Menunggu deployment.

**Bukti Pengujian:** Menunggu pengujian.

**Status:** Belum dimulai.

### Checkpoint 05 – Grafana Dashboard

**Aktivitas:** Belum dilaksanakan.

**Hasil Implementasi:** Menunggu konfigurasi dashboard.

**Bukti Pengujian:** Menunggu pengujian.

**Status:** Belum dimulai.

### Checkpoint 06 – Observability Integration

**Aktivitas:** Belum dilaksanakan.

**Hasil Implementasi:** Menunggu integrasi.

**Bukti Pengujian:** Menunggu pengujian.

**Status:** Belum dimulai.

### Checkpoint 07 – Incident Simulation & Troubleshooting

**Aktivitas:** Belum dilaksanakan.

**Hasil Implementasi:** Menunggu simulasi.

**Laporan Incident:** Belum tersedia.

**Bukti Pengujian:** Menunggu pengujian.

**Status:** Belum dimulai.

### Checkpoint 08 – Documentation & Portfolio

**Aktivitas:** Finalisasi dokumentasi dan publikasi project.

**Hasil Implementasi:** Dalam persiapan.

**Bukti Pengujian:** Menunggu finalisasi.

**Status:** Belum dimulai.

## 6. Hasil Pengujian

Pengujian awal Kubernetes berhasil. Pengujian komponen observability akan ditambahkan setelah deployment.

## 7. Struktur Repository

```text
kubernetes-observability-monitoring/
├── architecture/
├── dashboards/
├── docs/
├── helm/
├── kubernetes/
├── screenshots/
└── testing/
