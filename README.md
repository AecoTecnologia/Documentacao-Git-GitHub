## Introdução ao Git e GitHub
**Git** é um sistema de controle de versão distribuído que permite que você acompanhe as alterações no código-fonte durante o desenvolvimento de software. 
**GitHub** é uma plataforma de hospedagem de código-fonte baseada no Git que facilita o gerenciamento de projetos de software e a colaboração entre desenvolvedores

### Instalando o Git
- **Windows**: Baixe o instalador do site oficial do Git e siga as instruções.
- **MacOS**: Você pode instalar o Git usando o Homebrew com o comando `brew install git` no terminal.
- **Linux**: Instale o Git usando o gerenciador de pacotes da sua distribuição, por exemplo, `sudo apt-get install git` para distribuições baseadas em Debian/Ubuntu.
### Configurando o Git
Antes de começar a usar o Git, configure seu nome de usuário e endereço de email com os seguintes comandos:
```
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```
### Iniciando um Repositório no Git
Para iniciar um novo repositório Git no seu projeto local, navegue até o diretório do projeto no terminal e execute:
```
git init
```
### Clonando um Repositório
Para copiar um repositório existente no GitHub para a sua máquina local, use:
```
git clone https://github.com/usuario/repositorio.git
```
### Fazendo Commits
Para salvar suas alterações no histórico do repositório, use os seguintes comandos:
```
git add .
git commit -m "Mensagem do commit"
```
**Padrões de Mensagens de Commit**:
- **feat**: Introduz um novo recurso.
- **fix**: Corrige um bug.
- **wip**: Trabalho em progresso, não finalizado.
- **docs**: Alterações apenas nos documentos.
- **style**: Mudanças que não afetam o significado do código (espaçamento, formatação, etc.).
### Fazendo Merge
Para incorporar as alterações de uma branch (ramificação) em outra:
1. Mude para a branch que receberá as alterações com `git checkout branch_destino`.
2. Execute o comando `git merge branch_origem`.
### Pull Requests no GitHub
**Pull Requests** são propostas de mudança que você envia para um repositório no GitHub. Após a revisão, podem ser aceitas e mescladas ao projeto principal.

**Padrão de Mensagens dos Pull Requests**:
- Inclua um título claro e descritivo.
- Descreva detalhadamente o que sua mudança propõe e por que deve ser aceita.
- Referencie issues (problemas) relacionadas.
### Colaborando com Projetos
- **Fork**: Faça um "fork" do projeto para o qual deseja contribuir, criando uma cópia no seu perfil do GitHub.
- **Clone**: Clone o fork para sua máquina local e crie uma nova branch para suas alterações.
- **Pull Request**: Após fazer o commit das suas alterações no fork, envie um pull request para o repositório original.
