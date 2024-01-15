## Branches

Branches consistem em ramificações do repositório principal. Dessa forma, uma branch no Git é simplesmente um ponteiro móvel para um commit. O nome do branch padrão no Git é main. 

### 💻 Criando uma nova branch

```bash
$ git checkout -b nome-da-branch
Switched to a new branch 'nome-da-branch'
```

### 💻 Voltar para a branch main

```bash
$ git checkout main
Switched to branch 'main'
```

### 📁 Lista os últimos commits das Branches

```bash
$ git branch 
* main  
  outra-branch 
```

### 📁 Lista os últimos commits das Branches

```bash
$ git branch -v
* main  numero-commit commit 2 nome-commit
  outra-branch numero-commit-3 nome-commit
```

### 💻 Mesclar Branches

```bash
$ git merge nome-da-branch
```

### 💻 Deletar branch
```bash
$ git branch -d nome-da-branch
```

