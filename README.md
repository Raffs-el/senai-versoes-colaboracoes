# Projeto de introdução ao Git e GitHub (SENAI)

## 🎯 Objetivo

Este projeto tem como proposta a listagem de códigos que foram aplicados durante o módulo de versionamento do curso de programação front-end do SENAI com a intenção de especificar e praticar suas definições e finalidades, respectivamente. Além de ter simulado situações nas quais ocorrem conflitos no momento da mesclagem de *branchs*.

## 📃 Códigos utilizados

- `git init` : cria a estrutura inicial do repositório Git no computador local;
- `git config --global user.name` : define o nome de usuário no Git;
- `git config --global user.email` : define o email do usuário no Git;
- `git status` : rastreia alterações no repositório local;
- `git add .` : adiciona na *staging* todas as alterações feitas no repositório local;
- `git commit -m "nome da commit"` : salva e nomeia as alterações feitas;
- `git log` : visualiza o registro das *commits*;
- `git show número-da-commit` : visualiza o que foi feito na *commit* especificada;
- `git remote add origin url` : informa no repositório local a pasta remota;
- `git remote -v` : visualiza o repositório remoto;
- `git push -u origin main` : publica as alterações feitas na *main* no repositório remoto;
- `git pull` : baixa o repositório remoto;
- `git clone "link"` : clona a pasta do repositório remoto;
- `git checkout -b nome-da-branch` : cria uma nova *branch* e vai diretamente para ela;
- `git checkout main` : vai diretamente para a *main*;
- `git checkout nome-da-branch` : vai diretamente para a *branch* especificada;
- `git push -u origin nome-da-branch` : publica as alterações feitas na *branch* descrita;
- `git merge nome da branch` : adiciona o conteúdo da *branch* informada na atual;
- `git tag -a v número.da.versão -m "nome da tag"` : cria uma *tag* para marcar o ponto atual;
- `git tag` : visualiza as *tags* criadas;
- `git show nome da tag` : mostra informações sobre uma *tag* específica;
- `git push -u origin --tags` : publica as *tags* no repositório remoto;

##  👨‍💻 Autor do projeto

### ☞ [Rafael Miranda](https://github.com/Raffs-el) ⌨️ 