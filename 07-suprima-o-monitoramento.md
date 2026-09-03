# 07. Suprima o monitoramento

> Ignore arquivos e diretórios temporários.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)

---

## Itens desta seção (2)

### 1. Arquivo `.gitignore`

```gitignore
*.log
build/
temp-*
```

**O que este arquivo faz:**

<!-- TODO: Arquivo que define o que o Git deve ignorar. -->

**Quando usar / observação:**

<!-- TODO: Para impedir que arquivos indesejados sejam versionados. -->

---

### 2. `git ls-files --others --ignored --exclude-standard`

```bash
git ls-files --others --ignored --exclude-standard
```

**O que faz:**

<!-- TODO: Lista arquivos que estão sendo ignorados pelo Git. -->

**Quando usar / observação:**

<!-- TODO: Para verificar se as regras do .gitignore estão funcionando. -->

---

## Checklist deste arquivo

- [x] 1. Arquivo `.gitignore`
- [x] 2. `git ls-files --others --ignored --exclude-standard`

---

[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)
