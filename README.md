```bash
backend-golang/
│── cmd/
│   ├── api/
│   │   ├── api.go
│   ├── migrate/
│   │   ├── migrations/
│   │   ├── main.go
│   ├── main.go
│── ├── configs/
│   │   ├── envs.go
│   ├── db/
│   │   ├── db.go
│   ├── services/
│   │   ├── user/
│   │   │   ├── routes.go
│   │   │   ├── store.go
│   │   ├── auth/
│   │   │   ├── jwt.go
│   │   │   ├── jwt_test.go
│   │   │   ├── password.go
│   │   │   ├── password_test.go
│   │   ├── types/
│   │   │   ├── type.go
│   │   ├── utils/
│   │   │   ├── util.go
│── go.mod
│── go.sum
│── Dockerfile
│── docker-compose.yml
│── Makefile
│── README.md
```