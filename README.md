#  TopZ Homelab

Personal homelab stack running on a local machine with Docker.

## 📦 Stack

| Service | Port | Description |
|---|---|---|
| [Homepage](https://gethomepage.dev) | `3001` | Start page / Dashboard |
| [Uptime Kuma](https://github.com/louislam/uptime-kuma) | `3002` | Service monitoring |
| [Grafana](https://grafana.com) | `3003` | Metrics visualization |
| [Portainer](https://www.portainer.io) | `9000` | Docker management UI |
| [Netdata](https://www.netdata.cloud) | `19999` | Real-time system metrics |

## 🚀 Getting Started

```bash
git clone https://github.com/kittiponglnwza/Homelap.git
cd Homelap
docker compose up -d
```

เปิด `http://localhost:3001` แล้วใช้งานได้เลย

## 📁 Structure

```
Homelab/
├── docker-compose.yml
├── homepage/
│   ├── bookmarks.yaml
│   ├── services.yaml
│   ├── settings.yaml
│   └── widgets.yaml
└── README.md
```

## 📱 Access from other devices

เปลี่ยน `localhost` เป็น IP ของเครื่อง เช่น `http://192.168.x.x:3001`

> iPad และอุปกรณ์อื่นต้องอยู่ WiFi วงเดียวกัน
