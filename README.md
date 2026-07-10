# Media Server Local

Servidor doméstico de mídia com Docker, usando Jellyfin como interface principal para organização e reprodução de biblioteca local.

## Objetivo

Este projeto documenta a montagem incremental de um servidor de mídia local, com foco em organização, reprodução e automação da biblioteca.

A configuração é feita por etapas, permitindo testar cada serviço antes de avançar para o próximo.

## Serviços planejados

- Jellyfin: servidor de mídia
- qBittorrent: cliente de download
- Radarr: gerenciamento de filmes
- Sonarr: gerenciamento de séries
- Prowlarr: gerenciamento de indexadores
- Bazarr: gerenciamento de legendas
- Jellyseerr: interface de solicitações

## Estrutura local esperada

```text
media-server/
├── config/
│   └── jellyfin/
├── media/
│   ├── filmes/
│   └── series/
├── downloads/
├── docker-compose.yml
├── .env
└── docs/
```

# Download de bibliotecas para o QBitTorrent

https://github.com/qbittorrent/search-plugins/wiki/unofficial-search-plugins