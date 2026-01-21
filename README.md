# Amp

A self-hosted amp application.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/amp/main/docker-compose.yaml" | docker compose -f - up -d
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

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
