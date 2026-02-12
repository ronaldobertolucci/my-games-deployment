# My Games - Deployment

Sistema de gerenciamento de jogos com backend Spring Boot e frontend Angular.

## 🚀 Quick Start

### 1. Configurar variáveis de ambiente
```bash
cp .env.example .env
# Edite o .env com suas configurações
```

### 2. Subir a aplicação
```bash
docker compose up -d
```

### 3. Acessar

- **Frontend**: http://localhost
- **API**: http://localhost/api
- **Health Check**: http://localhost/health

## 🛠️ Comandos Úteis

### Ver logs
```bash
docker compose logs -f
docker compose logs -f backend
docker compose logs -f frontend
```

### Reiniciar serviços
```bash
docker compose restart
docker compose restart backend
```

### Parar tudo
```bash
docker compose down
```

### Parar e remover volumes
```bash
docker compose down -v
```

### Verificar status
```bash
docker compose ps
```