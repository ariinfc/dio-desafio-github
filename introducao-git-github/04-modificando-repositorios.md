
## Modificação de repositórios

### 💻 Adicionar arquivos e commits

```bash
$ git add .

$ git status
On branch main
No commits yet
Changes to be committed: <mudanças>

$ git commit -m"nome-do-commit"

$ git log
commit <hash-do-commit> (HEAD -> main)
Author: 
Date:  

    nome-do-commit

$ git status
On branch main
nothing to commit, working tree clean
```

### 💻 Desfazer repositório


```bash
$ rm -rf .git
$ git status
fatal: not a git repository (or any of the parent directories): .git
```

### 📁 Restaurar mudanças

```bash
$ git restore <nome-do-arquivo>
```

### 💻 Renomear último commit

```bash
$ git commit --amend -m"novo-nome-do-commit"
```

### 💻 Atualizar o repositório local
```bash
$ git pull
```

### 💻 Enviar alterações para o repositório remoto
```bash
$ git push -u origin main
```

