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
https://github.com/anamartinsr/artigo_dio.git
```
Abra o terminal:
- Digite e execute o seguinte comando com o link copiado do GitHub:
```
git clone <url_do_repositorio>

# Exemplo:
git clone <https://github.com/anamartinsr/artigo_dio.git>

```

Acesse a pasta do projeto:
```
cd <nome_da_pasta>

# Exemplo:
cd artigo_dio/
```

Dica: Ao digitar o nome da pasta no terminal, você pode pressionar a tecla TAB para completar automaticamente o nome.

Exemplo: cd arti + TAB → cd artigo_dio/

Abra o projeto no Visual Studio Code (opcional):
- Se você tiver o VS Code instalado, ainda no terminal, digite:

```
code .
```

Isso abrirá o projeto diretamente no VS Code.

Modifique algum arquivo ou crie um novo:
- Como o repositório foi criado com um README.md automático, ele será o único arquivo visível inicialmente.
- Para fins de demonstração, você pode alterar o conteúdo do README.md, por exemplo:

```
## Artigo Dio
Este é um projeto de exemplo para fins de demonstração
```

Envie as atualizações para o repositório remoto:
- Abra o terminal novamente (no exemplo, usamos o terminal do Git Bash integrado ao VS Code) e execute os seguintes comandos:
```
git status
```
- Mostra o status atual do projeto: arquivos modificados, adicionados ou excluídos.

Dica: O comando git status é um dos mais utilizados. Sempre execute-o antes de rodar comandos que afetem o repositório remoto — ele ajuda a verificar o que será enviado ou modificado.
```
git add .
```
- Adiciona todos os arquivos modificados à área de preparação (staging).
```
git commit -am "initial commit"
```
- Cria o commit com uma mensagem descritiva.
- A flag a adiciona automaticamente os arquivos que já estavam sendo monitorados.
```
git push
```
Envia suas alterações para o repositório remoto no GitHub.

Pronto! Suas modificações já estão publicadas no GitHub.

Demonstração: Clonando um repositório

## Principais comandos GIT
Saber os principais comandos do Git é um diferencial na sua vida profissional, mas relaxa, com o tempo e a prática do dia a dia você acaba pegando o jeito e decora os comandos, caso tenha dúvidas, é válido consultar a documentação oficial.


```
git init : Inicializa um repositório Git.
```
Quando começar a desenvolver um novo projeto.


```
git clone <url> : Clona um repositório remoto na sua máquina.
```
Para criar uma cópia local de um repositório já existente remoto.


```
git status : Mostra os arquivos modificados, adicionados ou removidos.
```
Para verificar o estado atual dos arquivos no repositório.


```
git add <arquivo> : Adiciona um arquivo à área de preparação.
```
Quando quer adicionar um arquivo para fazer o commit.


```
git add . : Adiciona todas as alterações à área de preparação.
```
Quando quer adicionar todos os arquivos para fazer o commit.


```
git commit -m "mensagem" : Salva as alterações com uma mensagem descrevendo o que foi modificado.
```
Para criar um commit no histórico do projeto.


```
git log : Mostra o histórico de commits.
```
Para revisar o que foi feito e por quem.


```
git branch : Lista todas as ramificações (branches) do seu repositório.
```
Para ver os fluxos de trabalho.


```
git checkout <branch> : Muda para outra branch.
```
Quando quer trabalhar em outra linha de desenvolvimento.


```
git checkout -b <nova-branch> : Cria e muda para uma nova branch.
```
Para iniciar o desenvolvimento de uma nova funcionalidade ou correção.


```
git merge <branch> : Junta outra branch à branch atual.
```
Quando finalizar uma tarefa e quiser integrar ao código principal.


```
git pull : Atualiza seu repositório local com as alterações do remoto.
```
Para manter seu projeto sincronizado antes de começar a trabalhar e evitar conflitos.


```
git push : Envia seus commits para o repositório remoto.
```
Para compartilhar suas alterações com o time no GitHub.


## Comandos GIT Nível Ninja:

git stash
O recurso de arquivamento temporário (ou "stashes ") das alterações feitas na sua cópia de trabalho permite que você trabalhe em outra coisa e, em seguida, volte e reaplique-as mais tarde. O "stashing" é útil se você precisa mudar rapidamente de contexto e trabalhar em outra coisa, mas está no meio de uma alteração no código e ainda não está pronto para fazer o commit.

Fonte: Atlassian (2024).
```
git stash           # guarda as mudanças
git stash pop       # aplica de volta
```
Dica: Você pode dar nome aos stashes:
```
git stash save "refatorando página inicial"
```
git reflog
Histórico secreto do que você já fez, mesmo que tenha perdido um commit ou branch. O Git rastreia atualizações no final das ramificações usando um mecanismo chamado logs de referência, ou "reflogs".

Fonte: Atlassian (2024).
```
git reflog
```


git reset vs git revert


git reset
Volta seu projeto para um commit anterior. Ideal pra desfazer algo que deu problema. Ele possui três formas principais de invocação. Essas formas correspondem aos argumentos da linha de comando . Os três argumentos correspondem aos três mecanismos internos de gerenciamento de estado do Git: a Árvore de Commits (Commit Tree ), o Índice de Staging e o Diretório de Trabalho. Os três tipos de reset são: .--soft, --mixed, --hard HEAD .

Fonte: Atlassian (2024).
```
git reset --soft HEAD~1    # volta 1 commit, mantém as mudanças e deixa no stage
git reset --hard HEAD~1    # volta 1 commit e apaga as mudanças
git reset --mixed HEAD~1   # volta 1 commit, mantém as mudanças mas tira do stage
```
Dica: Use com cuidado! O --hard apaga todas as mudanças.

Dica: Stage (ou "staging area") é uma área de preparação.

git revert Diferente do reset, o revert não apaga o histórico, ele cria um novo commit que desfaz as alterações do commit escolhido.

Em vez de remover o commit do histórico do projeto, ele descobre como inverter as alterações introduzidas pelo commit e anexa um novo commit com o conteúdo inverso resultante. Isso evita que o Git perca o histórico, o que é importante para a integridade do seu histórico de revisões e para uma colaboração confiável. Fonte: Atlassian (2024).

git revert <hash-do-commit>

Dica: O git revert abre o editor de mensagens de commit. Se quiser pular essa parte, use o flag --no-edit.
```
git revert <hash-do-commit> --no-edit
```

git blame
Sua função mais importante git blameé exibir metadados do autor anexados a linhas confirmadas específicas em um arquivo. É utilizado para explorar o histórico de um código específico e entender quem foi o último autor de cada linha, além de responder o que, como e por que o código foi adicionado. Mostra quem foi o responsável por cada linha de um arquivo. Excelente pra debugar.

Fonte: Atlassian (2024)
```
git blame nome-do-arquivo
```
git shortlog
O git shortlogcomando é uma versão especial do comando para criar anúncios de lançamento. Ele agrupa cada commit por autor e exibe a primeira linha de cada mensagem de commit. Esta é uma maneira fácil de ver quem está trabalhando em quê. Ótimo pra gerar relatórios de contribuição.

Fonte: Atlassian (2024).
```
git shortlog -s -n
```

## Padronização de Commits
No mundo do desenvolvimento, é comum adotarmos padrões para manter o projeto limpo, organizado e de fácil entendimento. Uma boa prática nesse sentido é a padronização das mensagens de commit. O commit semântico é uma convenção que busca melhorar a clareza e a eficácia desses registros, tornando cada mensagem objetiva e descritiva sobre a alteração feita no projeto. Esse padrão evita mensagens vagas como “ajustes”, “refatorei” ou “tela inicial”, promovendo uma comunicação mais clara entre os membros da equipe.

Fonte: Sujeito Programador (2024).



Estrutura do Commit Semântico
```
<tipo>(escopo): <mensagem>
```
tipo: o que foi feito
escopo: onde foi feito
mensagem: descrição breve da alteração


Tipos mais comuns de commits
feat: nova funcionalidade
fix: correção de bug ou erro
refactor: mudanças no código que não adicionam funcionalidades nem corrigem bugs (ex: reestruturações ou otimizações)
style: alterações de estilo (espaçamento, formatação, etc.) que não afetam a lógica do código
docs: alterações na documentação
perf: melhorias de performance
test: adição ou correção de testes
chore: tarefas de manutenção, como atualizações de dependências
hotfix: correção rápida de problemas em produção
cleanup: remoção de comentários, códigos mortos ou arquivos desnecessários

Para garantir que todos os commits estejam dentro do padrão estabelecido, podemos utilizar ferramentas como Husky e Commitlint.

## Husky
O Husky permite criar ganchos (hooks) do Git — ações automáticas que são executadas em momentos específicos, como antes de um commit ou um push. Com ele, conseguimos rodar verificações, testes e validar mensagens de commit.

Por exemplo: ao tentar fazer um commit, o Husky pode acionar o Commitlint para checar se a mensagem segue a estrutura correta.

## Commitlint
O Commitlint verifica se a mensagem de commit está no formato correto, baseado nas regras que você definir (por exemplo, seguir o padrão <tipo>(escopo): mensagem). Se a mensagem não estiver dentro do padrão, ele impede o commit até que a mensagem seja corrigida.

Instalação
1. Instale o Husky

No terminal, dentro do diretório do seu projeto, execute:
```
npm install --save-dev husky
```
Em seguida, inicialize o Husky:
```
npx husky init
```
Isso criará uma pasta .husky com um exemplo de hook pré-commit.

2. Instale o Commitlint

Ainda no terminal, instale as dependências do Commitlint:
```
npm install --save-dev @commitlint/config-conventional @commitlint/cli
```
3. Crie o arquivo de configuração do Commitlint

Crie o arquivo commitlint.config.js com o seguinte conteúdo:
```
echo "export default { extends: ['@commitlint/config-conventional'] };" > commitlint.config.js
```
verifique se a linha dentro do arquivo gerado está corretamente formatada. Se o conteúdo aparecer entre aspas duplas como string ("export default {...}"), remova as aspas para deixar como código JavaScript válido.

4. Configure o hook de commit

Dentro da pasta .husky, crie um novo arquivo chamado commit-msg:
```
npx husky add .husky/commit-msg
```
Depois, edite o conteúdo do arquivo .husky/commit-msg e cole o seguinte:
```
#!/usr/bin/env sh
# . "$(dirname "$0")/_/husky.sh"
npx --no-install commitlint --edit "$1"
```
Esse comando garante que, antes de qualquer commit, a mensagem será validada pelo Commitlint.

5. (Opcional) Configurar o pre-commit

Se quiser, você também pode adicionar comandos de teste ou lint no hook pre-commit. Exemplo de conteúdo do arquivo .husky/pre-commit:

# npm test
Basta descomentar ou adicionar comandos que devem rodar antes de cada commit.

## Curiosidades históricas sobre GIT e GitHub 
Você sabia que o Git foi criado em apenas 10 dias? Em 2005, Linus Torvalds, o mesmo criador do Linux, desenvolveu o Git após problemas com o BitKeeper, um sistema de versionamento que usava na época. O nome “GIT” também tem uma curiosidade por trás: Linus brincava dizendo que era uma gíria britânica para alguém “teimoso, desagradável ou cabeça-dura”, uma referência aos problemas que ele teve com os sistemas de versionamento da época.

Mas o comando git também carrega outros significados, como “Global Information Tracker” e “comando pequeno, mas poderoso”. Mesmo tendo sido criado em tão pouco tempo, o Git se tornou o sistema de controle de versão mais utilizado no mundo.

Já o GitHub foi criado em 2008 por quatro amigos, com a ideia de facilitar a hospedagem e o compartilhamento de repositórios Git, trazendo uma interface amigável. A plataforma foi rapidamente aceita pela comunidade. Em 2009, já contava com mais de 46 mil repositórios, e em 2011 ultrapassou o SourceForge, tornando-se o favorito dos desenvolvedores.

## O famoso mascote do GitHub é o Octocat:

Um polvo com cabeça de gato
Criado por Simon Oxley, o mesmo designer que fez o passarinho do Twitter
Virou um ícone do mundo dev e até possui versões colecionáveis.
Em 2018, o GitHub enfrentou um dos maiores ataques DDoS da história, mas também protagonizou uma das maiores movimentações do mercado de tecnologia: foi adquirido pela Microsoft por US$ 7,5 bilhões, em um marco histórico para a plataforma.


## Conclusão
Git e GitHub são ferramentas essenciais que abrem portas para uma nova forma de pensar e construir projetos. Quanto mais você usa, mais familiar se torna. Não se prenda somente a esse artigo, faça cursos, explore conteúdos e procure por documentações. Comece hoje mesmo, publique seus códigos, colabore e mostre ao mundo o seu potencial.



## Referências
KANSARA, Darshil. GitHub vs GitLab: Qual é o melhor em 2025? Radixweb, 5 ago. 2024. Disponível em: https://radixweb.com/blog/github-vs-gitlab.

GIT SCM. Git – Distributed Version Control System. Disponível em: https://git-scm.com/.

BALLERINI, Rafaella. Como criar um README para seu perfil GitHub. YouTube, 2022. Disponível em: https://youtu.be/TsaLQAetPLU?si=WCWaH-_WedEKGWUa

GITHUB DOCS. Gerenciando seu README de perfil. GitHub Documentation. Disponível em: https://docs.github.com/pt/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme

GITHUB DOCS. Sobre repositórios. GitHub Documentation. Acesso em: abr. 2025. Disponível em: https://docs.github.com/pt/repositories/creating-and-managing-repositories/about-repositories

OPEN SOURCE GUIDE. Which open source license is appropriate for my project? GitHub, 2025. Acesso em: abr. 2025. Disponível em: https://opensource.guide/legal/#which-open-source-license-is-appropriate-for-my-project

ATLASSIAN. Git Glossary. 2024. Disponível em: https://www.atlassian.com/br/git/glossary#commands. Acesso em: abr. 2025.
