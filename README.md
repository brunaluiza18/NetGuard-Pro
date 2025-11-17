# NetGuard-Pro
Atividade Modulo IA

# NetGuard Pro

## 📝 Visão Geral
NetGuard Pro é uma ferramenta de gestão de dispositivos e usuários em rede, projetada para administradores e equipes de TI. Permite visualizar dispositivos conectados, gerenciar permissões, aplicar políticas de acesso e gerar relatórios de atividades em tempo real.

## ✨ Recursos Principais
- Descoberta automática de dispositivos na rede (scan)
- Inventário de dispositivos com informações (IP, MAC, sistema operacional)
- Gerenciamento de usuários e roles (admin, operador, auditor)
- Aplicação de políticas de acesso por dispositivo/usuário
- Logs e relatórios de atividade
- Integração com LDAP/Active Directory (simulada)
- API RESTful para integração com outras ferramentas
- Painel web responsivo (exemplo básico incluído)
- Notificações e alertas (email/SMS/Slack — simulado)

## 🧱 Arquitetura / Tecnologias Utilizadas
- **Linguagem:** TypeScript (Node.js)
- **Framework Backend:** Express
- **Banco de Dados:** SQLite (para protótipo) / Postgres (produção)
- **Autenticação:** JWT
- **Testes:** Jest
- **Linting:** ESLint + Prettier
- **CI/CD:** GitHub Actions (exemplos)
- **Front-end:** React + Vite (opcional)

## 🖥️ Requisitos do Sistema
- Node.js >= 18
- npm ou yarn
- 1GB RAM (desenvolvimento)
- Porta 3000 disponível

## ⚙️ Instalação (desenvolvimento)
1. Clone:
```bash
git clone https://github.com/seu-usuario/netguard-pro.git
cd netguard-pro
