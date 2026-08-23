# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

<!-- atualiza o que foi mudado no github por outra pessoa, mas ainda sem incorporar -->

**Quando usar / observação:**

<!-- quando se quer ficar a par das modificacoes feitas no github -->

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

<!-- mescla as alteracoes feitas no git hub com sua branch local -->

**Quando usar / observação:**

<!-- usar apos git fetch -->

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

<!-- usar para enviar suas alteracoes para o github, especificando a branch a ser atulizada -->

**Quando usar / observação:**

<!-- apos todos os commits e altercoes estarem prontos para ser enviados -->

---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

<!-- basicamente fetch + merge juntos em um comando -->

**Quando usar / observação:**

<!-- para se atualizar e imediatamente trabalhar com as alteracoes feitas no github -->

---

## Checklist deste arquivo

- [x] 1. `git fetch [nome-remoto]`
- [x] 2. `git merge [nome-remoto]/[branch]`
- [x] 3. `git push [alias] [branch]`
- [x] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
