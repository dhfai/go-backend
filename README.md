```bash
backend-golang/
│── cmd/                     # Entry point aplikasi
│   ├── main.go              # Main file untuk menjalankan aplikasi
│── config/                  # Konfigurasi aplikasi
│   ├── config.go            # File konfigurasi
│── internal/                # Business logic utama aplikasi
│   ├── auth/                # Modul autentikasi
│   │   ├── handler.go       # HTTP handler untuk login & register
│   │   ├── service.go       # Business logic autentikasi
│   │   ├── repository.go    # Operasi database untuk user
│   │   ├── middleware.go    # Middleware JWT
│   │   ├── jwt.go           # Utilitas untuk JWT
│   ├── user/                # Modul user
│   │   ├── handler.go       # HTTP handler untuk user
│   │   ├── service.go       # Business logic user
│   │   ├── repository.go    # Operasi database untuk user
│   ├── profile/             # Modul profile
│   │   ├── handler.go       # HTTP handler untuk profile
│   │   ├── service.go       # Business logic profile
│   │   ├── repository.go    # Operasi database untuk profile
│   ├── productive-time/     # Modul produktif time
│   │   ├── handler.go       # HTTP handler untuk produktif time
│   │   ├── service.go       # Business logic produktif time
│   │   ├── repository.go    # Operasi database untuk produktif time
│── db/                      # Koneksi database & migrasi
│   ├── migrations/          # File migrasi database
│   ├── database.go          # Koneksi database
│── pkg/                     # Package utilitas
│   ├── hash/                # Utility untuk hashing password
│   │   ├── hash.go          # Implementasi hashing
│   ├── response/            # Utility untuk response JSON
│   │   ├── response.go      # Standardisasi response API
│── routes/                  # Definisi route aplikasi
│   ├── routes.go            # Router utama
│── .env                     # Konfigurasi environment
│── go.mod                   # File module Go
│── go.sum                   # Dependencies
│── Dockerfile               # Docker configuration
│── Makefile                 # Skrip untuk build/test
│── README.md                # Dokumentasi proyek
```