# Monitoramento do Nginx com Notificação por Email

Este projeto verifica o status do serviço Nginx em um sistema CentOS e envia um email quando o serviço está offline.

## Conteúdo do Projeto

- `script/monitor_nginx.sh`: Script para monitorar o status do Nginx.
- `services/monitor_nginx.service`: Arquivo de serviço do `systemd` para iniciar o monitor automaticamente.
- `docs/setup_instructions.md`: Instruções de instalação e configuração.

## Como Usar

1. Instale o Nginx e o Postfix.
2. Copie o script e o arquivo de serviço para os diretórios apropriados.
3. Ative o serviço `monitor_nginx.service` com o `systemd`.

Para mais detalhes, consulte `docs/setup_instructions.md`.

