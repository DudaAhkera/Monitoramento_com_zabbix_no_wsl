# Projeto: Monitoramento com Zabbix no WSL

## 🎯 Objetivo
Instalar e configurar o Zabbix Server em ambiente **Debian WSL2** com **MariaDB** e **Apache2**, acessível via navegador no Windows, para monitorar métricas de desempenho da CPU.

## ⚙️ Tecnologias utilizadas
- Debian WSL2
- Zabbix Server + Agent
- MariaDB
- Apache2 + PHP
- Linux troubleshooting (logs, processos, serviços)

## 🚀 Passos principais
1. Instalação dos pacotes necessários (`zabbix-server-mysql`, `zabbix-frontend-php`, `zabbix-agent`, `mariadb-server`, `apache2`).
2. Criação do banco `zabbix` e usuário `zabbix` com senha.
3. Configuração do arquivo `/etc/zabbix/zabbix_server.conf`:
   ```ini


