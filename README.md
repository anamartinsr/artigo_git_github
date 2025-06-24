# GIT vs GitHub: O que você precisa saber sobre essas tecnologias

Neste artigo, vamos descomplicar, de uma vez por todas, o que é GIT e GitHub, e explorar as funcionalidades mais usadas no dia a dia.

Vamos imaginar que você está desenvolvendo um trabalho em equipe na faculdade, onde cada integrante do grupo ficou com uma parte do projeto. Com isso, os participantes do grupo precisam desenvolver a sua parte e depois juntar tudo para finalizar o projeto com sucesso. Você acha que seria interessante se todos pudessem trabalhar simultaneamente, salvar suas alterações em versões do documento, visualizar as modificações dos colegas e até mesmo reverter para uma versão anterior, se necessário?

Então, com o Git e o GitHub essas são algumas das inúmeras funcionalidades oferecidas. Vamos explorar de forma prática como essas duas ferramentas funcionam, suas diferenças e como começar a usá-las.

Segundo Kansara (2024), o GitHub possui cerca de 56 milhões de usuários.

E você não pode ficar de fora!

## Introdução aos conceitos de GIT e GitHub.

### O que é Git?
Git é um sistema de controle de versão distribuído, desenvolvido pelo criador do núcleo do Linux, Linus Torvalds, no ano de 2005.

- Permite que várias pessoas trabalhem simultaneamente no mesmo projeto.
- Mantém o histórico completo das alterações.
- Distribuído – ao clonar um repositório Git, você tem uma cópia completa do projeto no seu computador, incluindo todo o histórico e versões anteriores.
- Open Source – oferece liberdade para compartilhar e modificar o software, garantindo que ele permaneça livre para todos os usuários (GIT SCM, 2025).




## O que é GitHub?
GitHub é uma plataforma de hospedagem de código, criada por Tom Preston-Werner, Chris Wanstrath e PJ Hyett em 2008.

- Serviço online que hospeda repositórios Git na nuvem.
- Centraliza e organiza repositórios públicos e privados.
- Permite documentação dos projetos através de README.md, wikis e gists.
- Possui uma comunidade ativa de código aberto, ideal para estudos, pesquisas e colaboração. É possível seguir perfis, fazer forks, adicionar estrelas em repositórios úteis e contribuir com outros projetos.
- Suporta automação de tarefas como testes, CI/CD e integrações.

## E qual é a relação entre o Git e o GitHub?
- Git encarrega-se do controle de versões do código.
- GitHub é a plataforma onde esse código é armazenado.

Guia do GIT:
Para fazer o versionamento do código, você precisa instalar e configurar o Git na sua máquina.


## Instalando o Git:
1. Windows
- Acesse: https://git-scm.com.
- Clique em "Download for Windows".
- Execute o instalador baixado.
- Aceite os termos e mantenha as opções padrão.
- Finalize clicando em "Install" e depois em "Finish".

2. Linux
- Em distribuições baseadas no Debian (como o Ubuntu), abra o terminal e execute:
  
``bash
sudo apt-get update
``

``bash
sudo apt-get install git
``

3. macOS
- Abra o terminal e digite: git
- Caso o Git não esteja instalado, o sistema irá sugerir a instalação automaticamente.
- Siga as instruções exibidas na tela.

## Configurando o Git:
Sempre que você realiza um commit, o Git registra quem foi o autor daquela alteração. Por isso, é necessário configurar seu nome e e-mail para que essas informações fiquem salvas no histórico.

### Essa configuração é a mesma para Windows, Linux e macOS.

Abra o terminal e execute os seguintes comandos:

``bash
git config --global user.name "Seu Nome"
``

``bash
git config --global user.email "seu@email.com"
``

Esses comandos definem seu nome e e-mail globalmente, e só precisam ser executados uma vez, logo após a instalação.

``bash
git config --list
``

Esse comando mostra as configurações globais do seu Git. Use para confirmar se está tudo certo após configurar nome e e-mail.
Após essa configuração, o seu Git está pronto para uso!


## Guia do GitHub
Para colaborar com outros usuários, armazenar seus repositórios Git na nuvem e utilizar as ferramentas disponíveis na plataforma, o primeiro passo é criar uma conta no GitHub.

