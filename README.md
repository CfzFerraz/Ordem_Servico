# Ordem de Serviço — Central de Tecnologia

> **Status: Em desenvolvimento**
>
> Este projeto ainda está em fase de desenvolvimento e **não possui banco de dados implementado**.

## Sobre o projeto

Sistema web para abertura, acompanhamento e gerenciamento de ordens de serviço (OS) do setor de Tecnologia da Informação.

A proposta é centralizar os chamados de TI, permitindo que os usuários registrem problemas e que a equipe de suporte acompanhe e atualize o andamento das solicitações.

## Status atual

- Portal de atendimento web em desenvolvimento.
- Abertura de ordens de serviço.
- Seleção de loja, setor/local, equipamento e tipo de problema.
- Possibilidade de anexar fotos em situações específicas.
- Consulta do status da ordem de serviço.
- Painel administrativo para acompanhamento das OS.
- Filtros e atualização de status no painel administrativo.
- **Banco de dados ainda não implementado.**
- A versão atual utiliza estruturas locais do navegador para testes e desenvolvimento.

## Estrutura do projeto

```text
Ordem_Servico/
├── css/
│   ├── admin.css
│   └── style.css
├── html/
│   └── admin.html
├── img/
│   ├── LOGO_GM.png
│   ├── logo_g+01.png
│   ├── logo_g+02.png
│   ├── logo_g+03.png
│   └── logo_g+04.png
├── js/
│   ├── admin.js
│   └── script.js
└── index.html
```

## Tecnologias

- HTML5
- CSS3
- JavaScript
- LocalStorage (uso temporário durante o desenvolvimento)

## Próximas etapas

- Implementação do banco de dados.
- Persistência das ordens de serviço em servidor.
- Autenticação e controle de usuários.
- Melhorias no painel administrativo.
- Histórico de alterações das OS.
- Melhorias de segurança e validação.
- Preparação para implantação em ambiente real.

## Observação

Este repositório representa uma versão de desenvolvimento do sistema. Funcionalidades, estrutura, interface e arquitetura podem ser alteradas conforme o projeto evolui.
