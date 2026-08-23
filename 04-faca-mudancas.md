# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

<!-- revisar as alteracoes
verificar o que está staged para ser commitado -->

**Quando usar / observação:**

<!-- antes de commitar, para saber quais arquivos falta add -->

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

<!-- mostrar o que foi alterado no arquivo antes de ir para staged -->

**Quando usar / observação:**

<!-- usar antes de .add -->

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

<!-- adiciona o arquivo no estado atual para envia-lo no commit -->

**Quando usar / observação:**

<!-- depois de modificar, antes de commitar -->

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

<!-- mostra  diferenca entre os arquivos prontos para commit e suas versoes anteriores -->

**Quando usar / observação:**

<!-- para verificar diferencas depois de ter feito .add -->

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

<!-- tira o arquivo de staged, porem mantem as alteracoes feitas -->

**Quando usar / observação:**

<!-- quando se quer modificar algo em arquivo staged -->

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

<!-- envia oficialmente as alteracoes feitas para historico de versionamento -->

**Quando usar / observação:**

<!-- quando se esta satisfeito com as alteracoes feitas -->

---

## Checklist deste arquivo

- [x] 1. `git status`
- [x] 2. `git diff`
- [x] 3. `git add [arquivo]`
- [x] 4. `git diff --staged`
- [x] 5. `git reset [arquivo]`
- [x] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
