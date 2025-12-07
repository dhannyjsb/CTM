# Cloudflare Tunnel Manager (CTM)

Desktop application untuk mengelola Cloudflare Tunnels dan port forwarding di Windows.

## 📥 Download

Download installer terbaru dari [Releases](https://github.com/dhannyjsb/CTM/releases)


## ✨ Features

- ✅ Kelola Cloudflare Tunnels melalui GUI
- ✅ Port forwarding: `localhost:port` → `domain.com`
- ✅ Multiple domain mappings dalam 1 tunnel
- ✅ Windows Service management (auto-start)
- ✅ Real-time status monitoring
- ✅ Auto-update system
- ✅ Multi-device support dengan token binding

## 🚀 Quick Start

1. Download installer dari [Releases](https://github.com/dhannyjsb/CTM/releases)
2. Run `CTM-Setup-x.x.x.exe` (as Administrator)
3. Input Cloudflare API Token
4. Select domain (zone)
5. Create tunnel & add port mappings
6. Install & start service

## 📋 Requirements

- Windows 10/11
- Cloudflare account dengan domain aktif
- Cloudflare API Token ([Create Token](https://dash.cloudflare.com/profile/api-tokens))
  - Permission: `Zone:Read`, `Account:Read`, `Cloudflare Tunnel:Edit`

## 🔧 Configuration

### Port Mapping Example:

```yaml
# localhost:3000 → app.example.com
# localhost:8080 → api.example.com
# localhost:5000 → admin.example.com
```

### Windows Service:

- Service name: `cloudflared`
- Auto-start: Optional (configurable)
- Run as: Administrator required

## 📝 Changelog

### v1.0.1 (Latest)
- Initial release
- Basic tunnel management
- Port mapping configuration
- Windows service integration
- Auto-update support

## ⚠️ Note

- Administrator privileges diperlukan untuk install Windows service
- Token API disimpan lokal (encrypted)
- Auto-update akan check update setiap app startup

## 🔗 Links

- [Cloudflare Tunnels Documentation](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/)
- [Report Issue](https://github.com/dhannyjsb/CTM/issues)

## 📄 License

Proprietary - © 2025 dhannyjsb

---

**Made with ❤️ for Cloudflare Tunnel management**
