# GIT E GITHUB

Guia prático para iniciantes.

### Instalação

https://git-scm.com/download

# SCENES

- [x] Você deseja criar pontos na história da produção do seu projeto
- [x] Você deseja verificar mudanças feitas no seu projeto

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

- [x] Você quer colocar seu projeto na nuvem.

- [x] Você vai pegar um projeto já iniciado, para trabalhar com o time
- [x] Você precisa resolver um conflito.
- [x] Antes de enviar a resolução, precisamos atualizar o projeto local.

- [x] Você precisa voltar um arquivo para um determinado momento da linha do tempo.
- [x] Você precisa recuperar algo deletado.

# COMANDOS

* `git init` // inicia a linha do tempo
* `git add` // adiciona ou atualiza mudanças para irem para a linha do tempo
- * `git add .` //adiciona todos os arquivos da pasta
- * `git add NOME DO ARQUIVO`// adiciona um arquivo especfico
* `git commit` // adiciona um ponto na linha do tempo
- *`git commit -m MENSAGEM` // comita o arquivo inserindo uma mensagem
* `git log` // visualiza os pontos na linha do tempo / commit
- * `git log -p`// verifica o status completo
- * `git log --oneline`// verifica o status em uma linha 
* `git status` // informa o estado das alterações do nosso projeto
* `git show` // apresenta determinado ponto na história
* `git branch` // gerenciar novas linhas do tempo
- * `git branch -D NOME_DA_BRANCH` // deleta uma branch criada
* `git checkout` // manipula as linhas do tempo
* `git merge` // unir linhas do tempo
- * `git merge NOME_DA_BRANCH`

### Enviar o repositório local para o repositório remoto
* `git remote add origin (link do github)`// linkar o repositorio local com o remoto
* `git push` // envia alterações locais para o repositório remoto
- *`git push -u origin master`
* `git clone` // clonar um projeto / repositório
* `git pull` // puxa do repositório remoto

### Clonar
*`git clone Link_do_repositorio_Github`
*`git checkout -b ____`