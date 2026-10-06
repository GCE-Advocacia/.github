# Projeto: Sistema de Gestão para Escritório de Advocacia 

**Matéria:** Gerência de Configuração e Evolução de Software (2026.2)  
**Professor:** Thiago Luiz de Souza  

## Sobre o Projeto
O sistema foi desenvolvido com o objetivo de apoiar a gestão de um escritório de advocacia, cobrindo presença online, recepção de leads, cadastro de clientes, controle de processos, movimentações, anotações internas e trilhas de auditoria. 

O projeto original foi idealizado e construído em uma matéria do semestre passado. Para este semestre (2026.2), o objetivo é mapear, estruturar e desenvolver melhorias contínuas arquiteturais e funcionais no sistema.

##  Equipe

| Foto | Nome | GitHub |
| :---: | :--- | :--- |
| <img src="https://github.com/nanecapde.png" width="50" style="border-radius:50%"> | Anne de Capdeville | [@nanecapde](https://github.com/nanecapde) |
| <img src="https://github.com/Arturhk05.png" width="50" style="border-radius:50%"> | Artur H. Krauspenhar | [@Arturhk05](https://github.com/Arturhk05) |
| <img src="https://github.com/Prg-maker.png" width="50" style="border-radius:50%"> | Daniel | [@Prg-maker](https://github.com/Prg-maker) |
| <img src="https://github.com/fabinsz.png" width="50" style="border-radius:50%"> | Fabio Gabriel | [@fabinsz](https://github.com/fabinsz) |
| <img src="https://github.com/MMcLovin.png" width="50" style="border-radius:50%"> | Gabriel Fernando | [@MMcLovin](https://github.com/MMcLovin) |
| <img src="https://github.com/guilhermezan42.png" width="50" style="border-radius:50%"> | Guilherme Costa | [@guilhermezan42](https://github.com/guilhermezan42) |
| <img src="https://github.com/isacostaf.png" width="50" style="border-radius:50%"> | Isabelle da Costa | [@isacostaf](https://github.com/isacostaf) |
| <img src="https://github.com/Jose1277.png" width="50" style="border-radius:50%"> | José Felipe Oliveira | [@Jose1277](https://github.com/Jose1277) |
| <img src="https://github.com/lucasbbranco.png" width="50" style="border-radius:50%"> | Lucas Branco | [@lucasbbranco](https://github.com/lucasbbranco) |
| <img src="https://github.com/mrodrigues14.png" width="50" style="border-radius:50%"> | Matheus Rodrigues | [@mrodrigues14](https://github.com/mrodrigues14) |
| <img src="https://github.com/Pabloo8.png" width="50" style="border-radius:50%"> | Pablo Cunha | [@Pabloo8](https://github.com/Pabloo8) |
| <img src="https://github.com/Bessazs.png" width="50" style="border-radius:50%"> | Vitor Pereira Bessa | [@Bessazs](https://github.com/Bessazs) |


##  Quadro de Contribuições

| **Integrante** | **Atividades / O que fez no projeto** | **Data** | **Commits / PRs** |
| :--- | :--- | :---: | :--- |
| **Gabriel, Fabio e Daniel** | Implementação inicial da funcionalidade de personalização das cores da Landing Page. | 12/09/26 | [feat: personalização inicial de cores](https://github.com/Prg-maker/tppe-advocacia-frontend/commit/8c84cd72b8e1f3da6deb619af950277ddcd49b86) |
| **Gabriel, Fabio e Daniel** | Adição do novo ColorPicker e funcionalidade para restaurar as cores para o padrão. | 13/09/26 | [feat: adiciona reset para o padrão e novo ColorPicker](https://github.com/Prg-maker/tppe-advocacia-frontend/commit/258abee21f8308bb5a9e28b24c27dd69fcb1eb5f) |
| **Gabriel, Fabio e Daniel** | Adição de tooltips e melhoria dos labels existentes na interface de personalização. | 13/09/26 | [feat: adiciona tooltips e melhora labels existentes](https://github.com/Prg-maker/tppe-advocacia-frontend/commit/f579dd79b6d0cb335dc4ef1ea21575b1601593c6) |
| **Anne, Pablo, Matheus** | Criação da estrutura de pagamentos no site e no banco de dados | 13/09/26 | [Commit 96921df](https://github.com/GCE-Advocacia/tppe-advocacia-backend/commit/96921df292e64ba2ac311bfeffcca77101d9df17) |
| **Matheus, Pablo, Anne** | Criação da Pagina "Pagamentos" com exibição de calendário e pagamentos | 14/09/26 | [Commit e23aea6](https://github.com/GCE-Advocacia/tppe-advocacia-frontend/commit/e23aea6475b74dda05326a0e39a5cb068f86caf4) |
| **Lucas, José e Guilherme** | Criação da estrutura de lançamentos financeiros no banco de dados e do módulo financeiro na API. | 14/09/26 | [PR backend #1](https://github.com/GCE-Advocacia/tppe-advocacia-backend/pull/1) |
| **Lucas, José e Guilherme** | Cadastro de entradas e saídas, listagem com filtro por período e resumo com totais e saldo na API, restritos ao administrador. | 14/09/26 | [PR backend #1](https://github.com/GCE-Advocacia/tppe-advocacia-backend/pull/1) |
| **Lucas, José e Guilherme** | Criação da página de controle financeiro, restrita a administradores, com cards de totais, saldo e tabela paginada. | 14/09/26 | [PR frontend #1](https://github.com/GCE-Advocacia/tppe-advocacia-frontend/pull/1) |
| **Lucas, José e Guilherme** | Cadastro de entradas e saídas pela tela, em um modal único, e filtro por período aplicado à tabela e aos cards. | 14/09/26 | [PR frontend #1](https://github.com/GCE-Advocacia/tppe-advocacia-frontend/pull/1) |
| **Isabelle, Arthur e Bessa** | Separação do componente de criação e edição de tarefas para permitir sua reutilização em processos. | 16/09/26 | — |
| **Isabelle, Arthur e Bessa** | Front: Criação de um espaço para tarefas na ficha de processo. | 16/09/26 | — |
| **Isabelle, Arthur e Bessa** | Permitir usuário adicionar uma tarefa direto pela ficha de um processo. | 16/09/26 | — |
| **Lucas, José e Guilherme** | Permissão por usuário para visualizar vencimentos na API: funcionário autorizado só lê, cadastro, edição e exclusão restritos ao administrador. | 05/10/26 | [PR backend #8](https://github.com/GCE-Advocacia/tppe-advocacia-backend/pull/8) |
| **Lucas, José e Guilherme** | Controle de acesso à página de Pagamentos por permissão, modo somente leitura para funcionário e opção de liberar ou negar vencimentos na tela de Usuários. | 05/10/26 | [PR frontend #10](https://github.com/GCE-Advocacia/tppe-advocacia-frontend/pull/10) |
| **Lucas, José e Guilherme** | Documentação da permissão de visualização de vencimentos: tarefa e critérios na US01, coluna no modelo físico e registro no status de RBAC. | 05/10/26 | [Commit 0f426ec](https://github.com/GCE-Advocacia/tppe-advocacia-docs/commit/0f426ecc534f762b086179dea2841bd9ccac3979) |
| **Pablo, Anne e Matheus** | Backend: Estruturação dos modelos de dados (`PaymentReminder`, tipos de lembrete `D-1` e `D-0`), repositório de consultas e rotas da API para histórico de lembretes. | 05/10/26 | [Commit c9a813d](https://github.com/GCE-Advocacia/tppe-advocacia-backend/commit/c9a813d2820f558d54f160ba2e7f3f53f3ecee05) |
| **Pablo, Anne e Matheus** | Backend: Implementação do `PaymentReminderService` (regras de envio, validação de e-mails, templates dinâmicos) e suíte de testes automatizados com serviço de e-mail. | 05/10/26 | [Commit efc3a34](https://github.com/GCE-Advocacia/tppe-advocacia-backend/commit/efc3a34648f712cced7a318e5631ab3a89185260) |
| **Anne, Pablo e Matheus** | Frontend: Integração do histórico de lembretes no modal de vencimentos (`VencimentoModal`), estilização das badges de status (`SENT`, `FAILED`, `NO_EMAIL`) e alerta para clientes sem e-mail. | 05/10/26 | [Commit 2af2a6d](https://github.com/GCE-Advocacia/tppe-advocacia-frontend/commit/2af2a6d65967a3062566aa25f5866b7128046583) |




