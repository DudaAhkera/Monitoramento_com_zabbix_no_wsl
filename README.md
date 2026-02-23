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


## Diagnóstico de erros:

systemctl não disponível no WSL → uso de ps aux e logs.

Erro [1045] Access denied → correção de credenciais no MariaDB e no zabbix_server.conf.


## Reinicialização do servidor e validação com curl e dashboard.

## 🛠️ Problemas resolvidos
### Falha de autenticação no banco (erro 1045).

Mensagem “servidor não está rodando” no frontend.

Adaptação de comandos sem systemd no WSL.


## 📊 Resultado
### Dashboard do Zabbix acessível via navegador no Windows.

Monitoramentos de CPU ativos e funcionando.

Ambiente pronto para expansão com novos hosts e alertas.

<img width="1396" height="842" alt="Screenshot-Monitoramento_Local" src="https://github.com/user-attachments/assets/11a442e0-b4b5-4dcc-9687-c01da2ef0f16" />


<img width="1396" height="852" alt="Screenshot-Monitoramento_Medio" src="https://github.com/user-attachments/assets/e4de5bb2-8997-4ae8-aff1-6708fde1510e" />




