## Instalação e configuração do Git no Windows

### 💻 Instalação 

- Acesse < https://git-scm.com/download/win >;
- Faça o download do instalador e execute;
- Aceite a licença e clique em “Next”, e siga configurando como desejar¹ e clicando em “Next”;
- Finalize clicando em “Install”, e “Finish”.

Em "Select Components“, deixe as opções “Git Bash Here” e “Git GUI Here” marcadas.

### 💻 Configuração

#### Configurações de nome e email

```bash
$ git config --global user.name "seunome" 
$ git config --global user.email seuemail@email.com 
```

#### Mudando o nome da Branch Padrão:
```bash
$ git config --global init.defaultBranch main
```

### Autenticando via token:

- Crie um token em settings/apps/tokens e copie.

```bash
$ git config credential.helper (cache/store)
$ git clone <url-do-repositorio>
```
- Insira login e token.
