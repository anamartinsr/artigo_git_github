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

## Criando sua conta
- Acesse: https://github.com
- No canto superior direito da página inicial, clique em Sign up.
- Preencha os dados solicitados:
* Endereço de e-mail.
* Crie uma senha segura.
* Escolha de um nome de usuário.
- Confirme que você não é um robô (verificação CAPTCHA).
- Confirme seu e-mail:
- Acesse sua caixa de entrada, copie o código recebido e cole no campo indicado na tela do GitHub.
- Escolha seu plano:
* Free (gratuito, ideal para começar).
* Team (plano pago, com recursos adicionais).
  
Após esses passos, sua conta estará ativa e pronta para uso.

Demonstração: Criando sua conta

## Personalize seu perfil
Ter um perfil bem estruturado e atualizado é essencial para quem deseja se destacar como profissional na área de tecnologia. O GitHub funciona como um portfólio online, onde estarão disponíveis seus projetos, as tecnologias que você utiliza e informações pessoais. Além disso, você pode usar seu perfil para se conectar com outras pessoas e colaborar em projetos open source, o que demonstra proatividade e domínio sobre as tecnologias.

### Informações pessoais
- Clique no seu ícone no canto superior direito e depois em "Your profile".
- Clique no botão "Edit profile", no canto direito da tela do perfil.
- Preencha com seus dados:
* Nome
* Bio (fale brevemente sobre você)
* Foto de perfil
* Localização
* Site pessoal ou LinkedIn
* Empresa
  
Clique em "Save" para salvar as alterações.

## Repositório Especial
O repositório especial é uma funcionalidade muito interessante do GitHub, pois permite que você personalize seu perfil com mais detalhes sobre sua jornada na tecnologia. Trata-se de um repositório com o mesmo nome de usuário da sua conta no GitHub. Quando você cria esse repositório, o GitHub entende que ele é especial e exibe o conteúdo do arquivo README.md diretamente na página inicial do seu perfil. Você pode usar toda a sua criatividade nesse espaço, pois não há um modelo fixo. Inclusive, vale a pena pesquisar outros perfis para se inspirar e ter ideias de como montar o seu próprio README.md.

Esse repositório é escrito em Markdown, a linguagem de marcação simples que o GitHub utiliza.

Exemplo básico de README.md

```
### Olá! Eu sou a Ana 👋

💻 Desenvolvedora Back-End
🚀 Apaixonada por APIs, integrações e boas práticas
📚 Estudando DevOps e Arquitetura de Software
📫 Me encontre: [LinkedIn](<https://linkedin.com/>)

<!-- GitHub Stats -->
![Ana's GitHub Stats](<https://github-readme-stats.vercel.app/api?username={SEU_USER_NAME}&show_icons=true&theme=dracula>)
```
Demonstração: Repositório Especial

## Criando um repositório
Um repositório é o elemento mais básico do GitHub. É um local onde você pode armazenar seu código, seus arquivos e o histórico de revisões de cada um deles. Os repositórios podem ter vários colaboradores e podem ser públicos ou privados, conforme o objetivo do projeto (GitHub Docs, 2025).

### Passo a passo para criar um repositório:
- Na página inicial, clique em Repositories.
- Clique em New.
- Preencha os campos:
Repository name: nome do seu repositório
Description (opcional): uma breve descrição do projeto
Public / Private: escolha se será público (qualquer pessoa pode ver) ou privado (somente você ou colaboradores autorizados)
Initialize this repository with a README (opcional): marque essa opção se quiser criar um README automaticamente.

O README.md é um arquivo com extensão Markdown utilizado para documentar o projeto. É muito importante que todos os repositórios tenham um README bem estruturado, para que qualquer pessoa que visualizar o projeto possa entender seu propósito, como executá-lo, as tecnologias utilizadas, os pré-requisitos, a licença, entre outras informações.

- Add .gitignore (opcional): escolha uma linguagem (ex: Node) para ignorar arquivos desnecessários (como node_modules) ou arquivos sensíveis que não devem ser enviados ao GitHub (como .env, private.key)
- Choose a license (opcional): selecione uma licença.
- A licença define como outras pessoas podem usar seu código.

Se você quiser que outras pessoas usem, distribuam, modifiquem ou contribuam com seu projeto, é essencial incluir uma licença de código aberto. Mesmo que o repositório esteja público no GitHub, ninguém pode utilizar legalmente nenhuma parte do seu código sem uma permissão explícita. Por isso, adicionar uma licença é uma forma de proteger seu trabalho e deixar claro o que está autorizado (Open Source Guide, 2025).

### Quando usar uma licença?
Quando você quer que outras pessoas possam usar, contribuir ou aprender com seu código

### Quando não usar?
Quando for um projeto privado, pessoal ou apenas para testes

Por fim, clique em Create repository.

Demonstração: Licenses
Demonstração: Criando um repositório

## Clonando um repositório e enviando atualizações
Depois de criar o repositório, o próximo passo é cloná-lo. O git clone é um utilitário de linha de comando utilizado para copiar um repositório existente para sua máquina local (ATLASSIAN, 2024).

Acesse o repositório que deseja clonar:
- Clique no botão verde Code
- Copie o link HTTPS, por exemplo:
```
https://github.com/ribbeiroana/artigo_dio.git
```
Abra o terminal:
- Digite e execute o seguinte comando com o link copiado do GitHub:
```
git clone <url_do_repositorio>

# Exemplo:
git clone <https://github.com/ribbeiroana/artigo_dio.git>

```

Acesse a pasta do projeto:
```
cd <nome_da_pasta>

# Exemplo:
cd artigo_dio/
```

Dica: Ao digitar o nome da pasta no terminal, você pode pressionar a tecla TAB para completar automaticamente o nome.

Exemplo: cd arti + TAB → cd artigo_dio/
