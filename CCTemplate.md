# 📝 Guia de Commits (Conventional Commits)

Este guia segue o padrão de **Conventional Commits**, ideal para manter o histórico do projeto organizado, legível e automatizável (CI/CD, changelogs, etc).

---

## ✅ Tipos de Commits

### 🔧 `feat:` Commits de Funcionalidades
Usado para adicionar uma **nova funcionalidade** ao sistema.

**Exemplo:**
```bash
feat: adiciona filtro de busca por categoria
```
### 🐞 `fix:` Commits de Correções
Usado para corrigir bugs ou comportamentos indesejados.
**Exemplo:**
```bash
fix: corrige bug na ordenação de produtos
```

### 📚 `docs:` Commits de Documentação
Usado para mudanças em arquivos de documentação (README, comentários, etc.).
**Exemplo:**
```bash
docs: atualiza README com instruções de instalação
```

### 🎨 style: Commits de Estilo
Usado para mudanças de formatação que não afetam a lógica do código.
**Exemplo:**
```bash
style: remove espaços em branco desnecessários
```
### ♻️ refactor: Commits de Refatoração
Usado para mudanças internas que não alteram o comportamento externo, apenas melhoram o código.
**Exemplo:**
```bash
refactor: separa lógica de autenticação em módulo próprio
```
### 🧪 test: Commits de Testes
Usado para adição ou modificação de testes automatizados.
**Exemplo:**
```bash
test: adiciona teste unitário para função de login
```
### 🧹 chore: Commits de Tarefas Auxiliares
Usado para tarefas que não alteram o código de produção (dependências, configurações).
Exemplo:
```bash
chore: atualiza dependências do projeto
```
### ⚡ perf: Commits de Performance
Usado para melhorias de desempenho.
**Exemplo:**
```bash
perf: otimiza consulta SQL para produtos em estoque
```
### 🔄 ci: Commits de Integração Contínua
Usado para mudanças em scripts de CI/CD, como GitHub Actions ou GitLab CI.
**Exemplo:**
```bash
ci: adiciona step de testes ao GitHub Actions
```
### 🏗️ build: Commits de Build
Usado para mudanças que afetam o sistema de build ou empacotamento (Webpack, Docker, etc.).
**Exemplo:**
```bash
build: configura Webpack para produção
```
### ⏪ revert: Commits de Reversão
Usado para desfazer um commit anterior.
**Exemplo:**
```bash
revert: desfaz refatoração que quebrou o login
```
🧠 Dica: Estrutura de Commit

<tipo>: <descrição curta>

<corpo opcional explicando o que foi feito, por quê e observações técnicas>
Exemplo completo:

feat: adiciona sistema de avaliação por estrelas

- Permite usuários avaliarem produtos de 1 a 5
- Integração com backend via API
- Interface atualizada com estrelas interativas
Pode colar isso em qualquer editor de texto e salvar como:

📄 COMMIT_GUIDE.md


---
