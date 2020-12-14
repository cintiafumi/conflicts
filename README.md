# Git

<img src="./img/version-control-amico.png" alt="Representação de árvore de controle de versionamento de uma desenvolvedora" width="300" style="display: block; margin: 0 auto;">

[1. Fluxo de trabalho](#fluxo-de-trabalho)

[2. Conflitos](#conflitos)

[3. Dicas](#dicas)

---

## Fluxo de trabalho

<a href="https://youtu.be/w3jLJU7DT5E" target="_blank">Vídeo GitHub :octocat:</a>
<small> Idioma: 🇺🇸 | Legenda: 🇧🇷</small>

<img src="./img/gitflow.png" alt="git flow" width="500">

<small>Fonte: <a href="https://codigomaromba.com/2019/01/02/git-gitflow-usar-ou-nao-usar/" target="_blank">Código Maromba</a> 🇧🇷</small>

---

## Conflitos

<img src="./img/edit-conflict.png" alt="A representation of an edit conflict" width="500">

<small>Fonte: <a href="https://en.wikipedia.org/wiki/Edit_conflict" target="_blank">Wikipedia</a></small>

---

## Dicas

### Mensagem de commit

<a href="https://vidadeprogramador.com.br/uploads/2017/07/tirinha1713.png"><img src="https://vidadeprogramador.com.br/uploads/2017/07/tirinha1713.png" alt="Conversa entre dois desenvolvedores sobre mensagem de commit" title="git blame alonso" width="500" target="_blank" /></a>

<small>Fonte: <a href="https://vidadeprogramador.com.br/" target="_blank">Vida de Programador 🇧🇷</a></small>

A padronização de mensagens de commit facilita o entendimento entre desenvolvedores.

Uma forma seria o formato do **Commit Amigão**:

- **feat** (nova funcionalidade para o usuário)
- **style** (formatação geral no código, como lint. Não confundir com CSS)
- **refactor** (refatoração de código de produção)
- **test** (adicionar/refatorar testes)
- **fix** (correção de bug para o usuário)
- **docs** (mudanças na documentação)
- **chore** (atualização de tarefas ou código que não está relacionado a código em produção)

<small>Fonte: <a href="https://github.com/BeeTech-global/bee-stylish/tree/master/commits" target="_blank">Guia do Commit Amigão</a> 🇧🇷</small>

### Emojis em commits

Exemplo de mensagens de commit contendo emoji:
<img src="./img/emoji-commit.png" width="500">

<small>Fonte: <a href="https://medium.com/brainny-smart-solutions/padroniza%C3%A7%C3%A3o-de-commits-com-gitmoji-ef0af535f3a4" target="_blank">Medium</a> 🇧🇷</small>

Guia de emojis para cada tipo de commit:

<img src="./img/gitmoji.png" width="500">

| Imagem                | GMF shortcode           | Quando usar                                          |
| --------------------- | ----------------------- | ---------------------------------------------------- |
| :art:                 | `:art:`                 | Melhorar a estrutura / formato do código.            |
| :zap:                 | `:zap:`                 | Melhorar desempenho.                                 |
| :fire:                | `:fire:`                | Remover código ou arquivos.                          |
| :bug:                 | `:bug:`                 | Corrigir um bug.                                     |
| :ambulance:           | `:ambulance:`           | Hotfix crítico.                                      |
| :sparkles:            | `:sparkles:`            | Introduzir novas funcionalidades.                    |
| :rocket:              | `:rocket:`              | Coisas de deploy.                                    |
| :lipstick:            | `:lipstick:`            | Adicionar ou atualizar UI e arquivos de estilização. |
| :tada:                | `:tada:`                | Início de um projeto.                                |
| :white_check_mark:    | `:white_check_mark:`    | Adicionar ou atualizar testes.                       |
| :bookmark:            | `:bookmark:`            | Release / Version tags.                              |
| :rotating_light:      | `:rotating_light:`      | Corrigir compiler / warnings de linter.              |
| :construction:        | `:construction:`        | Trabalho em andamento (WIP).                         |
| :green_heart:         | `:green_heart:`         | Corrigir build de CI.                                |
| :arrow_down:          | `:arrow_down:`          | Downgrade de dependências.                           |
| :up:                  | `:up:`                  | Upgrade de dependências.                             |
| :pushpin:             | `:pushpin:`             | Fixar as dependências em versões específicas.        |
| :construction_worker: | `:construction_worker:` | Adicionar ou atualizar sistema de build de CI.       |

<small>Fonte: <a href="https://gitmoji.dev/" target="_blank">Gitmoji</a> 🇺🇸</small>
