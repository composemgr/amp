## 👋 Welcome to amp 🚀

AMP (Application Management Panel) - Game server management panel

## 📋 Description

AMP (Application Management Panel) - Game server management panel

## 🚀 Services

- **amp**: mitchtalmadge/amp-dockerized:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/amp/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/amp" ~/.local/srv/docker/amp
cd ~/.local/srv/docker/amp
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install amp
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:8097

## 📂 Volumes

- `./volumes/config/amp` - Data storage
- `./volumes/data/amp` - Data storage

## 🔍 Logging

```shell
docker compose logs -f amp
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
