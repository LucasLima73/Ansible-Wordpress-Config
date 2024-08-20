# Guia de Configuração de Ambiente WordPress e MySQL com Ansible

Este guia explica como configurar um ambiente WordPress e MySQL usando Ansible. O playbook configura um servidor web com WordPress e um servidor de banco de dados MySQL.

## Pré-requisitos

Antes de começar, certifique-se de que você tenha o seguinte:

1. **Servidores**:
   - Um servidor para hospedar o WordPress.
   - Um servidor para o banco de dados MySQL.

2. **Acesso SSH**:
   - Acesso SSH aos servidores com um usuário com privilégios de `sudo`.

3. **Ansible**:
   - Ansible instalado na sua máquina local. Você pode instalar o Ansible usando o comando:
     ```bash
     sudo apt update && sudo apt install ansible -y
     ```
