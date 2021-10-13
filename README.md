# DIO-curso-trabalhando-com-git-e-gitlab-na-pratica
Anotações do Curso Trabalhando com Git e GitLab na prática da Digital Innovation One

*Professor: Osnir Cunha*

### Tópico Conceitos Básicos do Git

**Aula - Introdução e objetivos do curso**

Git e GitLab

**Aula - Conceitos sobre Git e Fluxo de trabalho**

Versionamento = Controle de versões diferentes de um documento

VCS - Version Control System

Quem? 

O que? 

Quando? 

Por que?

GIT - DVCS - Distribuido Version Control System

Git Remote

Cada cópia é um repositório completo

Push = empurrar

Pull = Puxar

Branch = Ramos

Branch master ou main ou principal

Features em paralelo

E como fazer a integração novamente ao branch principal

Fluxo de trabalho

Não versionado

Não Modificado

Modificado

Staged

Git add

Commit

Remove

**Aula - Passo a passo para criar um repositório**

Prática

git init

git --help

tree -l

git status

**Aula - Configurações e commits**

git config user.name "michael jackson"

git config user.email "michael.jackson@inter.com.br"

vim .gitignore

#Mavem

target/

git add *

git commit -m "Adiciona o .gitignore com exclusão da target"

git log

vim .gitignore

#intelliJ

.idea

git config -l | grep alias

git acm "Adiciona exclusão IntelliJ"

git status

**Aula - Criando branches**

git checkout -b feature1

git log

git status

vim pom.xml

git status

git acm "Adiciona Mave"

git switch master

git switch -c frature2

vim README.md

git add *

git acm "Adiciona README.md"

**Aula - Sobre merge e rebase**

Merge master > feature2

git checkout feature2

git log --graph --online --all

git merge master

Rebase master > feature1

Reescreve a árvore

git checkout feature1

git rebase master

### Tópico - Como usar o GitLab para seus projetos

**Aula - Introdução ao GitLab**

Gerenciamento de repositórios 

- Similar ao Github e Bitbucket
- Open source
- Organização de repositórios em grupos
- CI/CD

**Aula - Interface da plataforma e criação de projeto**

Criar novo projeto

Criar a partir do template

Depois de criar ele oferece algumas configurações

**Aula - Apresentação do projeto no IntelliJ**

IDE utilizada em Java Community

Clicar na aba Git

Menu Git

Manage Repositories

Fetch busca informações do repositório remoto

**Aula - Como realizar o merge request**

Mergin Request, uma solicitação de um branch para outro branch

Criar um merge request

**Aula - Desenvolvendo uma pipeline e GitLab CI**

Gitlab CI/CD 

Continuos Delivery

Estudar

**Aula - Visualizando a execução da pipeline**

Runners imagens compartilhadas, pode demorar um pouco

**Aula - Dúvidas e comentários finais**

Squash agrupar dois commits

**Aula - GitLab**

https://gitlab.com/dio-git_and_gitlab
