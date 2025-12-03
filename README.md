# 📘 Guia Prático de Git e GitHub  

Este arquivo apresenta comandos básicos para começar a usar **Git** e **GitHub** em projetos individuais ou colaborativos. 


```sh
# Configuração LOCAL (apenas para este repositório)
git config user.name "Seu Nome Completo"
git config user.email "seu.email@exemplo.com"

# Configuração GLOBAL (para todos os repositórios no seu computador)
git config --global user.name "Seu Nome Completo"
git config --global user.email "seu.email@exemplo.com"

# Ver configurações atuais
git config --list

# Ver apenas nome e email
git config user.name
git config user.email

# Clonar repositório
git clone URL

# Adicionar mudanças
git add .

# Criar commit
git commit -m "mensagem"

# Envia para o GitHub 
git push origin main

# Conecta repositório local com o repositório remoto
git remote add origin URL

# Atualizar projeto
git pull

# Visualizar histórico de commits
git log

# Visualizar status atual do repositório
git status

# Certifica de estar no branch main atualizado
git checkout main
git pull origin main

# Cria uma nova branch para desenvolvimento
git branch nomedabranch

# Muda para o branch chamada develop
git checkout develop

# Cria e muda para o branch chamada develop
git checkout -b develop = git branch develop e git checkout develop

# Envia branch para o GitHub
git push -u origin develop 

# Baixa informações sobre branches remotos
git fetch origin

```







