# Bot Support

Repositório estruturado para o desenvolvimento de um bot de suporte e automação em Node.js (Discord.js v14), focado em atendimento operacional, segurança e organização de logs.

## 🚀 Sobre o Projeto

Este projeto tem como objetivo estruturar a base técnica para a gestão de atendimento em servidores de grande porte. A arquitetura foi pensada para garantir estabilidade, clareza nos fluxos de suporte e controle rigoroso de permissões e auditoria.

## 📂 Arquitetura

A estrutura do projeto utiliza um padrão modular para facilitar a manutenção e o dimensionamento das funcionalidades:

```text
src/
├── commands/     # Comandos de barra (Slash Commands)
├── events/       # Manipuladores de eventos do Discord
└── index.js      # Ponto de inicialização do cliente
🛠️ Stack Tecnológica
Runtime: Node.js

Framework: Discord.js (v14)

Controle de Versão: Git & GitHub

📌 Escopo de Desenvolvimento
[ ] Implementação de painel de atendimento via botões e formulários (Modals).

[ ] Sistema de transcrição de tickets para auditoria da moderação.

[ ] Tratamento centralizado de erros e respostas protegidas (ephemeral).

[ ] Gestão segura de variáveis de ambiente (.env).
