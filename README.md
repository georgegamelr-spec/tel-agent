# Tel-Agent

Open Source AI Phone/Chat Gateway for enterprise communication.

## Features
- 🤖 AI-powered chat and voice interactions
- 📞 Telephony integration (SIP)
- 🌐 Multi-channel support (Telegram, WhatsApp, Web)
- 🔐 Enterprise-grade security
- 🚀 Scalable n8n automation workflows

## Deployment

### Docker Compose
```bash
docker-compose -f docker-compose.yml up -d
```

### Public Widget
**URL**: https://193-123-75-1.sslip.io/widget/A3DexBfxHOXUu7DMIz4jOE4oYQ6yjpfx

### n8n Automations
**URL**: https://n8n.193-123-75-1.sslip.io

## Architecture
- **API**: Node.js/Express (port 39472)
- **Web UI**: React frontend (port 39471)
- **Orchestration**: Caddy reverse proxy
- **Automation**: n8n workflows

## Environment Setup
See `.env.example` for configuration.

---
**Deployment Status**: Active on Oracle VPS (193.123.75.1)
**Last Updated**: Oct 6, 2026
