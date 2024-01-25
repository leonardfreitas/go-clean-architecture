# Desafio GoExpert - Clean Architecture

## External required dependencies

- [migrate](https://github.com/golang-migrate/migrate)

## Getting Started

### Pre Build Commands

```bash:
go mod tidy
```

```bash:
docker-compose up -d
```

```bash
make migrations
```

### Build Commands

```bash
go build -o server ./cmd/ordersystem && ./server
```
