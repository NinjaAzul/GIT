# Comandos GIT

### Básico
- [x] git init - criará um repositório local do GIT
- [x] git clone - é usado para copiar um repositório
- [x] git add - adiciona um arquivo para seu próximo commit
- [x] git commit - criará uma cópia das mudanças e salva no diretório GIT
- [x] git push - move os arquivos locais para o repositório remoto

### Branching e Merging
- git branch - listará suas branches
- git checkout - troca para outra branch e verifica o seu diretório de trabalho
- git merge - mescla o histórico das branch's específicas dentro da branch atual
- git log - mostra todos os commits no histórico da branch atual

### Make a Change
- git status - lista arquivos novos ou modificados ainda não commitados
- git diff - lista alterações e conflitos
- git add [file] - coloca o arquivo para commit
- git reset [file] - tira os arquivos que estavam prontos para commit e continua com as alterações atuais do arquivo
- git commit -m "[descriptive message]" - leva os arquivos como eles estão na área de preparação e os armazena permanentemente no diretório Git.

### Synchronize
- git remote add <name> <url> - cria uma nova conexão para um repositório remoto
- git fetch - pega todas as mudanças da origin (sem merge/mesclar)
- git pull - pega todas as últimas alterações da origin e mescla
- git push - é usado para fazer upload das mudanças do repositório local para o repositório remoto origin

### Commits Convencionais/Conventional Commits
```sh
  $ git commit -m "<tipo>[escopo opcional]: <descrição>"
```
#### Exemplo
```sh
  $ git commit -m 'chore: commit-message-here' 
```
  - FIX - resolve um bug
  - FEAT - inicia a implementação de uma funcionalidade
  - CHORE - trabalho em progresso de uma funcionalidade
  - REFACTOR - ajuste sem mudar lógica - refatoração
  - TEST - inplementa testes automatizados
  - STYLE - mudanças de formatação do código - LINT
  - PERF - ajustes de performance
  - DOCS - insere documentação
  - CI - ajuste nas configurações do CI
  - BUILD - ajuste nas configurações de build
