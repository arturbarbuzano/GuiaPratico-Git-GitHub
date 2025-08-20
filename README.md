# 📘 Guia Prático de Git e GitHub  

Este arquivo apresenta um passo a passo simples para começar a usar **Git** e **GitHub** em projetos individuais ou colaborativos.  

---

## 🚀 Passo a Passo  

### 🔸 1. Criar sua conta no GitHub  
Se ainda não possui, registre-se em: [GitHub](https://github.com/).  

### 🔸 2. Instalar o Git  
Baixe e configure o **Git** no computador:  
🔗 [Download Git](https://git-scm.com/)  

### 🔸 3. Instalar o Visual Studio Code  
Instale o editor **VS Code**:  
🔗 [Download VS Code](https://code.visualstudio.com/)  

### 🔸 4. Criar um repositório remoto  
No **GitHub**, crie um **novo repositório público** chamado `scm´.  

### 🔸 5. Clonar o repositório no computador  

```sh
git clone https://github.com/SEU-USUARIO/scm.git

```
### 🔸 6. Criar o arquivo inicial
No VS Code, crie um arquivo inicial como por exemplo `index.html´ e adicione um conteúdo simples em HTML.

### 🔸 7. Configurar Git
Antes de dar início ao código, configure seu nome e e-mail no terminal do Git para possibilitar a conexão entre o GitHub e sua máquina.
```sh
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```

### 🔸 8. Salvar alterações no GitHub
No terminal, execute:
```sh
git add .
git commit -m "Meu primeiro commit"
git push

```

### 🔸 9. Adicionar colaborador
No Github, vá em Configurações > Colaboradores e convide um colega, depois aguarde ele aceitar o convite.

### 🔸 10. Fluxo do colaborador
Após aceitar o convite, o colaborador clona o mesmo repositório:
```sh
git clone https://github.com/SEU-USUARIO/scm.git
```
Em seguida, edita o arquivo e envia as alterações:
```sh
git add .
git commit -m "Alteração arquivo index.html"
git push
```
### 🔸 11. Atualizar o repositório local
Se o seu colaborador acabou de realizar o commit e você está editando no arquivo da sua máquina desde antes dele terminar, utilize o seguinte código para trazer as mudanças feitas pelo colaborador:
```sh
git pull
```

### 🔸 12. Resumo
```sh
# Configuração inicial
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"

# Clonar repositório
git clone URL

# Adicionar mudanças
git add .

# Criar commit
git commit -m "mensagem"

# Enviar alterações
git push

# Atualizar projeto
git pull
```







