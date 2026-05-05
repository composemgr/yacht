## 👋 Welcome to yacht 🚀

Web interface for managing Docker containers

## 📋 Description

Web interface for managing Docker containers

## 🚀 Services

- **app**: selfhostedpro/yacht:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/yacht/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/yacht" ~/.local/srv/docker/yacht
cd ~/.local/srv/docker/yacht
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install yacht
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:59096

## 📂 Volumes

- `./volumes/config/yacht` - Data storage

## 🔍 Logging

```shell
docker compose logs -f app
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
