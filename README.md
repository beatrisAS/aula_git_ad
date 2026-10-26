<div align="center">

# 🌿 Fundamentos de Git e GitHub

### Bootcamp de Analista de Dados Júnior · Generation Brasil

**Praticando versionamento de código: commits, branches, merges e trabalho com repositórios remotos.**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20Aprendizado-2ea44f?style=for-the-badge)

</div>

---

## 🎯 Sobre este repositório

Este projeto foi criado durante o **Bootcamp de Analista de Dados da Generation Brasil**. O objetivo é consolidar, na prática, os conceitos de **versionamento de código com Git e GitHub**: registrar o histórico de alterações, trabalhar com ramificações (branches), unir trabalhos com merge e sincronizar tudo com um repositório remoto.

## 📚 Conceitos Abordados

**1. Ciclo de vida dos arquivos**
- **Untracked:** arquivo novo, ainda não rastreado pelo Git.
- **Modified:** arquivo rastreado que sofreu alterações.
- **Staged:** alterações preparadas para entrar no próximo commit.
- **Committed:** alterações registradas com segurança no histórico.

**2. Commits**
- Criação de um histórico de alterações claro e seguro.
- Boas práticas para escrever mensagens de commit descritivas.

**3. Branches e Merge**
- Criação de ramificações para desenvolver sem afetar a `main`.
- Navegação entre branches.
- União de branches com merge e noções de resolução de conflitos.

**4. Repositório local e remoto**
- Conexão entre o repositório na máquina e o repositório no GitHub.
- Envio e atualização de código com push e pull.

---

## 🛠️ Comandos de Git Praticados

**🔄 Estado e histórico**
- `git status`: verificar o estado e o rastreamento dos arquivos.
- `git log --oneline`: consultar o histórico de commits de forma resumida.
- `git diff`: visualizar as alterações ainda não commitadas.

**💾 Commits**
- `git add .`: adicionar todas as alterações à área de preparação.
- `git commit -m "mensagem"`: registrar as mudanças com uma descrição clara.
- `git revert <hash>`: desfazer um commit criando um novo commit que o reverte.

**🌿 Branches e Merge**
- `git branch`: listar as branches existentes.
- `git branch nome-da-branch`: criar uma nova branch.
- `git checkout nome-da-branch` ou `git switch nome-da-branch`: mudar de branch.
- `git checkout -b nome-da-branch`: criar e já mudar para a nova branch.
- `git merge nome-da-branch`: unir uma branch à branch atual.
- `git branch -d nome-da-branch`: excluir uma branch já mesclada.

**☁️ Repositório remoto (GitHub)**
- `git remote add origin <url>`: configurar a conexão com o repositório na nuvem.
- `git push origin main`: enviar as atualizações para o GitHub.
- `git pull origin main`: trazer as atualizações do GitHub para a máquina.
- `git clone <url>`: copiar um repositório remoto para a máquina.

---

## 📁 Arquivo de Prática

- 📄 `Turma.py`: arquivo usado como base para os testes de alteração, commits, branches e merges via linha de comando.

## 🚀 Como reproduzir localmente

Para clonar este repositório e testar na sua máquina, execute no terminal:

```bash
# 1. Clonar o repositório
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git

# 2. Entrar na pasta do projeto
cd NOME-DO-REPOSITORIO

# 3. Criar uma branch para praticar
git checkout -b minha-branch

# 4. Fazer uma alteração, registrar e unir à main
git add .
git commit -m "Minha alteração de teste"
git checkout main
git merge minha-branch
```
