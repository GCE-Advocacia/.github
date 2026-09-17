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
| <img src="https://github.com/Bessazs.png" width="50" style="border-radius:50%"> | Vitor Pereira Bessa | [@Bessazs](https://github.com/Bessazs) |
| <img src="https://github.com/MMcLovin.png" width="50" style="border-radius:50%"> | Gabriel Fernando | [@MMcLovin](https://github.com/MMcLovin) |
| <img src="https://github.com/fabinsz.png" width="50" style="border-radius:50%"> | Fabio Gabriel | [@fabinsz](https://github.com/fabinsz) |
| <img src="https://github.com/guilhermezan42.png" width="50" style="border-radius:50%"> | Guilherme Costa | [@guilhermezan42](https://github.com/guilhermezan42) |
| <img src="https://github.com/isacostaf.png" width="50" style="border-radius:50%"> | Isabelle da Costa | [@isacostaf](https://github.com/isacostaf) |
| <img src="https://github.com/lucasbbranco.png" width="50" style="border-radius:50%"> | Lucas Branco | [@lucasbbranco](https://github.com/lucasbbranco) |
| <img src="https://github.com/mrodrigues14.png" width="50" style="border-radius:50%"> | Matheus Rodrigues | [@mrodrigues14](https://github.com/mrodrigues14) |
| <img src="https://github.com/Pabloo8.png" width="50" style="border-radius:50%"> | Pablo Cunha | [@Pabloo8](https://github.com/Pabloo8) |
| <img src="https://github.com/Prg-maker.png" width="50" style="border-radius:50%"> | Daniel | [@Prg-maker](https://github.com/Prg-maker) |


##  Quadro de Contribuições

| **Integrante**               | **Atividades / O que fez no projeto**                                                               | **Data** | **Commits / PRs**                                                                                                                                                   |
| ---------------------------- | --------------------------------------------------------------------------------------------------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Isabelle, Arthur e Bessa** | Separação do componente de criação e edição de tarefas para permitir sua reutilização em processos. | 16/09/26 | —                                                                                                                                                             |
| **Isabelle, Arthur e Bessa** | Front: Criação de um espaço para tarefas na ficha de processo.                                      | 16/09/26 | —                                                                                                                                                             |
| **Isabelle, Arthur e Bessa** | Permitir usuário adicionar uma tarefa direto pela ficha de um processo.                             | 16/09/26 | —                                                                                                                                                             |
| **Gabriel, Fabio e Daniel**  | Implementação inicial da funcionalidade de personalização das cores da Landing Page.                | 12/09/26 | [feat: personalização inicial de cores](https://github.com/Prg-maker/tppe-advocacia-frontend/commit/8c84cd72b8e1f3da6deb619af950277ddcd49b86)                 |
| **Gabriel, Fabio e Daniel**  | Adição do novo ColorPicker e funcionalidade para restaurar as cores para o padrão.                  | 13/09/26 | [feat: adiciona reset para o padrão e novo ColorPicker](https://github.com/Prg-maker/tppe-advocacia-frontend/commit/258abee21f8308bb5a9e28b24c27dd69fcb1eb5f) |
| **Gabriel, Fabio e Daniel**  | Adição de tooltips e melhoria dos labels existentes na interface de personalização.                 | 13/09/26 | [feat: adiciona tooltips e melhora labels existentes](https://github.com/Prg-maker/tppe-advocacia-frontend/commit/f579dd79b6d0cb335dc4ef1ea21575b1601593c6)|
| **Anne, Pablo, Matheus**  | Criação da estrutura de pagamentos no site e no banco de dados                                      | 13/09/26 | [Commit 96921df](https://github.com/GCE-Advocacia/tppe-advocacia-backend/commit/96921df292e64ba2ac311bfeffcca77101d9df17)|
| **Matheus, Pablo, Anne**  | Criação da Pagina "Pagamentos" com exibição de calendário e pagamentos                              | 14/09/26 | [Commit e23aea6](https://github.com/GCE-Advocacia/tppe-advocacia-frontend/commit/e23aea6475b74dda05326a0e39a5cb068f86caf4)|
| **Lucas, José e Guilherme** | Back: criação da tabela `financial_transactions` e do módulo financeiro, com tipo de lançamento e valores em Decimal. | 14/09/26 | [PR backend #1](https://github.com/GCE-Advocacia/tppe-advocacia-backend/pull/1) |
| **Lucas, José e Guilherme** | Back: cadastro de entradas e de saídas financeiras, restritos ao perfil de administrador. | 14/09/26 | [PR backend #1](https://github.com/GCE-Advocacia/tppe-advocacia-backend/pull/1) |
| **Lucas, José e Guilherme** | Back: listagem paginada de lançamentos com filtro por período e erro próprio para período inválido. | 14/09/26 | [PR backend #1](https://github.com/GCE-Advocacia/tppe-advocacia-backend/pull/1) |
| **Lucas, José e Guilherme** | Back: resumo financeiro com total de entradas, total de saídas e saldo calculados no banco. | 14/09/26 | [PR backend #1](https://github.com/GCE-Advocacia/tppe-advocacia-backend/pull/1) |
| **Lucas, José e Guilherme** | Front: página de controle financeiro em `/financeiro`, restrita a administradores, com cards de totais, saldo e tabela paginada. | 14/09/26 | [PR frontend #1](https://github.com/GCE-Advocacia/tppe-advocacia-frontend/pull/1) |
| **Lucas, José e Guilherme** | Front: modal único de cadastro de entradas e saídas, aceitando o valor com vírgula ou ponto. | 14/09/26 | [PR frontend #1](https://github.com/GCE-Advocacia/tppe-advocacia-frontend/pull/1) |
| **Lucas, José e Guilherme** | Front: filtro por período com listagem e resumo buscados juntos, descartando respostas obsoletas. | 14/09/26 | [PR frontend #1](https://github.com/GCE-Advocacia/tppe-advocacia-frontend/pull/1) |
| **Lucas, José e Guilherme** | Testes automatizados nos dois repositórios: 50 testes no backend (86,10% de cobertura) e testes e2e da tela financeira. | 14/09/26 | [PR backend #1](https://github.com/GCE-Advocacia/tppe-advocacia-backend/pull/1)<br>[PR frontend #1](https://github.com/GCE-Advocacia/tppe-advocacia-frontend/pull/1) |



