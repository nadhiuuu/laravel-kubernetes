<div align="center">
  <h1>🚀 Laravel with Kubernetes (Minikube)</h1>
  <p><strong>A modern Laravel 13 application containerized and orchestrated with Kubernetes</strong></p>
  
  ![PHP Version](https://img.shields.io/badge/PHP-8.3%2B-777BB4?style=flat-square&logo=php)
  ![Laravel Version](https://img.shields.io/badge/Laravel-13.7-FF2D20?style=flat-square&logo=laravel)
  ![License](https://img.shields.io/badge/License-MIT-success?style=flat-square)
</div>

---

## 📋 Tentang Proyek

Proyek ini adalah aplikasi Laravel modern yang dirancang untuk memenuhi tugas Mata Kuliah DevOps Minggu ke-12 yaitu deployment di Kubernetes menggunakan Minikube. Aplikasi ini sudah dikonfigurasi dengan Docker container dan Kubernetes manifest files untuk deployment yang mudah dan scalable.

## 🛠️ Persyaratan Sistem

Sebelum memulai, pastikan Anda sudah menginstall:

### Requirement Minimum
- **PHP** >= 8.3
- **Composer** >= 2.0
- **Node.js** >= 18.0 dan **npm** >= 9.0
- **Docker** >= 20.0
- **Minikube** >= 1.30
- **kubectl** >= 1.20

### Requirement Development
- **Git**
- **VS Code** atau editor pilihan Anda
- **Docker Desktop** (opsional, untuk local development)

---

## 📁 Struktur Proyek

```
laravel-minikube/
├── app/                      # Application code
│   ├── Http/                # Controllers & Middleware
│   ├── Models/              # Eloquent Models
│   └── Providers/           # Service Providers
├── config/                  # Configuration files
├── database/                # Migrations & Seeders
├── k8s/                     # Kubernetes manifests
│   ├── laravel.yaml        # Deployment & Pod
│   ├── mysql.yaml          # MySQL deployment
│   └── service.yaml        # Service definitions
├── public/                  # Public assets
├── resources/               # Views & Assets
│   ├── css/
│   ├── js/
│   └── views/
├── routes/                  # API & Web routes
├── storage/                 # File storage & logs
├── tests/                   # Test suites
├── vendor/                  # Composer dependencies
├── dockerfile               # Docker image definition
├── composer.json            # PHP dependencies
├── package.json             # JavaScript dependencies
├── vite.config.js           # Vite configuration
├── phpunit.xml              # PHPUnit configuration
└── artisan                  # Artisan CLI

---

<div align="center">
  <p>Made with ❤️ for Kubernetes & Laravel</p>
  <p>⭐ Jika berguna, jangan lupa star repository ini!</p>
</div>
