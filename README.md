# HOLA MUNDO, BIENVENIDO A ESTE REPOSITORIO QUE NO TIENE NADA DEL OTRO MUNDO 

# 📘 Guia Básico de Git e GitHub

Guia simples dos principais comandos Git para clonar repositórios, criar branches, salvar alterações e enviar para o GitHub.

---

## 📥 Clonar repositório

```bash
git clone URL_DO_REPOSITORIO
```

Baixa o projeto do GitHub para o seu computador.

---

## 📂 Entrar na pasta do projeto

```bash
cd nome-da-pasta
```

Entra na pasta do repositório clonado.

---

## 🔍 Ver status do repositório

```bash
git status
```

Mostra:

- branch atual  
- arquivos modificados  
- arquivos novos  
- arquivos prontos para commit  

---

## 🌿 Trabalhando com Branches

Branch = linha paralela de desenvolvimento para testar mudanças sem afetar a principal.

### 📌 Listar branches

```bash
git branch
```

Mostra todas as branches. A atual tem `*`.

---

### 🆕 Criar nova branch

```bash
git branch nome-da-branch
```

Cria uma branch baseada na atual.

---

### 🔄 Trocar de branch

```bash
git checkout nome-da-branch
```

Muda para a branch escolhida.

---

## ➕ Adicionar arquivos

```bash
git add .
```

Adiciona todos os arquivos modificados para preparação.

---

## 💾 Criar commit

```bash
git commit -m "descrição da alteração"
```

Salva uma nova versão das mudanças.

---

## ☁️ Enviar para o GitHub

```bash
git push origin nome-da-branch
```

Envia os commits para o repositório remoto.

---

## 🔀 Pull Request

Depois do push:

1. Abra o repositório no GitHub  
2. Clique em **Compare & Pull Request**  
3. Confirme o Pull Request  

---

## 🚀 Fluxo completo de trabalho

```bash
git clone URL
cd pasta
git branch branch-teste
git checkout branch-teste
git add .
git commit -m "minha alteração"
git push origin branch-teste
```

---

## ✅ Observações

- Aviso LF/CRLF no Windows não é erro  
- Use branches para testar mudanças  
- Faça commits frequentes  
- Escreva mensagens claras

- <img width="733" height="999" alt="image" src="https://github.com/user-attachments/assets/be564c51-7002-4027-8594-6b22a7a660f4" />

