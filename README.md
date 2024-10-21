# Workstation Tools

Bem-vindo ao repositório **Workstation Tools**! Este projeto contém scripts que automatizam e agilizam a configuração e preparação da minha máquina de trabalho, focando em ambientes Ubuntu.

## ⚠️ Aviso
Os scripts aqui fornecidos são projetados especificamente para distribuições Ubuntu, com suporte para versões principais 18+. Se você estiver usando uma distribuição diferente, será necessário adaptar os scripts conforme as peculiaridades do sistema.

## 🚀 Objetivo
O objetivo deste repositório é automatizar o processo de instalação de ferramentas essenciais, economizando tempo e garantindo consistência na configuração da minha workstation para desenvolvimento e administração de sistemas.

## 📋 Pré-requisitos
Antes de começar, você precisará de um ambiente Ubuntu com acesso a internet e permissões de administrador para executar comandos com `sudo`.

## 🔧 Instalar o Ansible
O primeiro passo para usar este repositório é garantir que o Ansible esteja instalado em sua máquina. Execute os comandos abaixo para instalar o Ansible, além de outras ferramentas necessárias como `git` e `unzip`:

```bash
sudo apt update && sudo apt install ansible unzip git -y

## Aplicar as configurações via Ansible

ansible-playbook ./workstation_automation.yml --ask-become-pass
