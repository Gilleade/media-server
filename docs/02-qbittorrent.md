# Etapa 02 - qBittorrent

## Objetivo

Instalar e validar o qBittorrent em Docker, usando Web UI para gerenciamento local de downloads.

Nesta etapa, o objetivo é confirmar que:

- o container sobe corretamente;
- a Web UI abre na rede local;
- o usuário consegue autenticar;
- a senha inicial é alterada;
- os downloads completos são salvos em `/downloads/complete`;
- os downloads incompletos são salvos em `/downloads/incomplete`.

## Serviço usado

- qBittorrent

## Porta padrão

```text
8080
```

# 10. Atualizar `README.md`

Na seção de documentação por etapa, adicione:

```md
- [Etapa 02 - qBittorrent](docs/02-qbittorrent.md)
```