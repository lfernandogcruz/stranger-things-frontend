<!--
# Boas vindas ao repositório frontend do projeto de Deploy - Stranger Things!

Aqui você vai encontrar os locais para colocar suas repostas relativas aos requisitos de frontend.

**Lembre-se**: coloque as respostas apenas dos requisitos que contém o seguinte direcionamento:

  - Adicione os comandos utilizados, de maneira sequencial, ao README do frontend.

**Nota**: Este direcionamento está presente no [repositório](https://github.com/tryber/sd-020-stranger-things) em que os requisitos do projeto são destrinchados.


# Boas vindas ao repositório do projeto Stranger Things!

Para realizar o projeto, atente-se a cada passo descrito a seguir, e se tiver qualquer dúvida, nos envie por _Slack_! #vqv 🚀

Aqui você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto a partir deste repositório, utilizando uma branch específica e um _Pull Request_ para colocar seus códigos.

# Termos e acordos

Ao iniciar este projeto, você concorda com as diretrizes do Código de Conduta e do Manual da Pessoa Estudante da Trybe.

# Entregáveis

<details>
  <summary><strong>🤷🏽‍♀️ Como entregar</strong></summary><br />

  Para entregar o seu projeto você deverá criar um Pull Request em **cada um destes** repositórios:
  
  Tribo A: 
  - [Repositório com o back-end](https://github.com/tryber/sd-020-a-stranger-things-backend);

  - [Repositório com o front-end](https://github.com/tryber/sd-020-a-stranger-things-frontend).
  
  Tribo B: 
  - [Repositório com o back-end](https://github.com/tryber/sd-020-b-stranger-things-backend);

  - [Repositório com o front-end](https://github.com/tryber/sd-020-b-stranger-things-frontend).

  Lembre-se de que você pode consultar o nosso conteúdo sobre [Git & GitHub](https://course.betrybe.com/intro/git/) sempre que precisar!

</details>

<details>
  <summary><strong>👨‍💻 O que deverá ser desenvolvido</strong></summary><br />

  Você vai adaptar e configurar os projetos descritos nesse README para que seja feito o deploy deles. Você vai colocar os projetos front-end e back-end no ar com o `Heroku`, utilizando o `Docker` em ambiente de produção. Além disso, você vai alterar alguns comportamentos aplicando os conceitos vistos no conteúdo. 

  ## Desenvolvimento

  Adapte e configure os projetos descritos nesse *README* para que seja feito o deploy utilizando `Docker` por meio do `Heroku`.

</details>

<details>
  <summary><strong>🗓 Data de Entrega</strong></summary><br />
  
  * Este projeto é individual
  * É `1` dia de projeto
  * Data para entrega regular do projeto: `13/09/2022 - 14:00h`

</details>

# Orientações

<details>
  <summary><strong>‼️ Antes de começar a desenvolver</strong></summary><br />

  1. Clone os **dois** repositórios:
Tribo A
  - `git clone git@github.com:tryber/sd-020-a-stranger-things-backend.git`
  - `git clone git@github.com:tryber/sd-020-a-stranger-things-frontend.git`
  
Tribo B
  - `git clone git@github.com:tryber/sd-020-b-stranger-things-backend.git`
  - `git clone git@github.com:tryber/sd-020-b-stranger-things-frontend.git`

  2. Navegue entre as pastas dos repositórios que você acabou de clonar:

  Tribo A
  - `cd sd-020-a-stranger-things-backend`
  - `cd sd-020-a-stranger-things-frontend`
  
  Tribo B
  - `cd sd-020-b-stranger-things-backend`
  - `cd sd-020-b-stranger-things-frontend`

  3. Instale as dependências dos dois projetos:

  - `npm install`

  3. Para rodar localmente os projetos, execute o script de start do `package.json`:

  - `npm start`

  4. Crie uma branch a partir da branch `master` para cada um dos repositórios:

  - Verifique se você está na branch `master`
    - Exemplo: `git branch`.
  - Se você não estiver na branch `master`, mude para a branch `master`
    - Exemplo: `git checkout master`
  - Agora crie uma branch à qual você vai submeter os `commits` dos seus projetos:
    - Você deve criar uma branch no seguinte formato: `nome-de-usuario-nome-do-projeto`
    - Exemplo:
      Tribo A
      - `git checkout -b joaozinho-sd-020-a-stranger-things-backend`
      - `git checkout -b joaozinho-sd-020-a-stranger-things-frontend`
      
      Tribo B
      - `git checkout -b joaozinho-sd-020-b-stranger-things-backend`
      - `git checkout -b joaozinho-sd-020-b-stranger-things-frontend`
      
  5. Adicione a sua branch com o novo `commit` ao repositório remoto:

  - Usando o exemplo anterior:
    Tribo A
    - `git push -u origin joaozinho-sd-020-a-stranger-things-backend`
    - `git push -u origin joaozinho-sd-020-a-stranger-things-frontend`
  
    Tribo B
    - `git push -u origin joaozinho-sd-020-b-stranger-things-backend`
    - `git push -u origin joaozinho-sd-020-b-stranger-things-frontend`

  6. Crie um novo `Pull Request` _(PR)_:

  * Vá até a página de _Pull Requests_ dos repositórios no GitHub: 
  Tribo A
  [Backend](https://github.com/tryber/sd-020-a-stranger-things-backend/pulls) | [Frontend](https://github.com/tryber/sd-020-a-stranger-things-frontend/pulls);
  Tribo B
  [Backend](https://github.com/tryber/sd-020-b-stranger-things-backend/pulls) | [Frontend](https://github.com/tryber/sd-020-b-stranger-things-frontend/pulls);

  * Clique no botão verde _"New pull request"_;

  * Clique na caixa de seleção _"Compare"_ e escolha a sua branch **com atenção**;

  * Clique no botão verde _"Create pull request"_;

  * Adicione uma descrição para o _Pull Request_ e clique no botão verde _"Create pull request"_;

  * **Não se preocupe em preencher mais nada por enquanto!**;

  * Volte até a página de _Pull Requests_ do repositório e confira se o seu _Pull Request_ está criado;
  Tribo A [link](https://github.com/tryber/sd-020-a-stranger-things-backend/pulls) 
  Tribo B [link](https://github.com/tryber/sd-020-b-stranger-things-backend/pulls) 

  * Volte até a página de _Pull Requests_ do repositório e confira se o seu _Pull Request_ está criado;
  Tribo A [link](https://github.com/tryber/sd-020-a-stranger-things-frontend/pulls) 
  Tribo B [link](https://github.com/tryber/sd-020-b-stranger-things-frontend/pulls) 

  * ⚠ **Observação: Os PRs não devem ser abertos neste repositório, apenas nos outros dois repositórios.** ⚠

</details>

<details>
  <summary><strong>⌨️ Durante o desenvolvimento</strong></summary><br />

  * ⚠ **PULL REQUESTS COM ISSUES NO LINTER NÃO SERÃO AVALIADAS. ATENTE-SE PARA RESOLVÊ-LAS ANTES DE FINALIZAR O DESENVOLVIMENTO!** ⚠

  * Faça `commits` das alterações que você realizar no código regularmente.

  * Lembre-se de sempre atualizar o repositório remoto após um (ou alguns) `commits`. 

  * Os comandos que você utilizará com mais frequência são:
    1. `git status` _(para verificar o que está em vermelho - fora do stage - e o que está em verde - no stage)_;
    2. `git add` _(para adicionar arquivos ao stage do Git)_;
    3. `git commit` _(para criar um commit com os arquivos que estão no stage do Git)_;
    4. `git push -u nome-da-branch` _(para enviar o commit para o repositório remoto na primeira vez que fizer o `push` de uma nova branch)_;
    5. `git push` _(para enviar o commit para o repositório remoto após o passo anterior)_.

</details>

<details>
  <summary><strong>🤝 Depois de terminar o desenvolvimento (opcional)</strong></summary><br />

  Para sinalizar que o seu projeto está pronto para o _"Code Review"_ dos seus colegas, faça o seguinte:

  - Vá até a página **DO SEU** _Pull Request_, adicione a label de _"code-review"_ e marque seus colegas:

    - No menu à direita, clique no _link_ **"Labels"** e escolha a _label_ **code-review**;

    - No menu à direita, clique no _link_ **"Assignees"** e escolha **o seu usuário**;

    - No menu à direita, clique no _link_ **"Reviewers"** e digite `students`, selecione o time `tryber/students-sd-0x`.

  Caso tenha alguma dúvida, [aqui tem um video explicativo](https://vimeo.com/362189205).

  ⚠ **Lembre-se que garantir que todas as _issues_ comentadas pelo Linter estão resolvidas!** ⚠

</details>

<details>
  <summary><strong>🕵🏿 Revisando um pull request</strong></summary><br />

  Use o conteúdo sobre [Code Review](https://course.betrybe.com/real-life-engineer/code-review/) para te ajudar a revisar os _Pull Requests_.

</details>

<details>
  <summary><strong>🎛 Linter</strong></summary><br />

  Usaremos o [ESLint](https://eslint.org/) para fazer a análise estática do seu código.

  Este projeto já vem com as dependências relacionadas ao _linter_ configuradas nos arquivos `package.json`.

  Para poder rodar o `ESLint` em um projeto basta executar o comando `npm install` dentro do projeto e depois `npm run lint`. Se a análise do `ESLint` encontrar problemas no seu código, tais problemas serão mostrados no seu terminal. Se não houver problema no seu código, nada será impresso no seu terminal.

  Você pode também instalar o plugin do `ESLint` no `VSCode`. Para isso, basta fazer o download do [plugin `ESLint`](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) e instalá-lo.

</details>

<details>
  <summary><strong>🛠 Testes</strong></summary><br />

  ### Backend

  Todos os requisitos do projeto serão testados **automaticamente** por meio do `Jest`. Basta executar o comando abaixo:

  ```bash
  npm test
  ```


  ### Frontend

  Todos os requisitos do projeto serão testados **automaticamente** por meio do `Cypress`. Basta executar um dos comandos abaixo:

  ```bash
  npm run cypress:open // (Com interface)
  npm run cy // (via CLI)
  ```

</details>

<details>
  <summary><strong>🏗️ Deploy - Stranger Things</strong></summary><br />

  Esse repositório contém as instruções e os requisitos para o projeto de Deploy com Heroku. O código base para o desenvolvimento do projeto está dividido em duas partes: a)uma API de back-end utilizando Node.js e Express; e b)um front-end com React. Abaixo estão disponíveis os links de acesso aos respectivos repositórios:

Tribo A
  - [Repositório com o front-end](https://github.com/tryber/sd-020-a-stranger-things-frontend);

  - [Repositório com o back-end](https://github.com/tryber/sd-020-a-stranger-things-backend).
  
  
Tribo B
  - [Repositório com o front-end](https://github.com/tryber/sd-020-b-stranger-things-frontend);

  - [Repositório com o back-end](https://github.com/tryber/sd-020-b-stranger-things-backend).
  

  A seguir, temos algumas explicações sobre a estrutura base e alguns comportamentos dessas aplicações. Você explorará esses pontos durante o projeto, alterando o código preexistente.

  Lembre-se de que se tratam de projetos base. Sendo assim, ao longo do desenvolvimento, você vai identificar pontos a serem alterados com o objetivo de aplicar as práticas que vimos durante o curso. Mas não se preocupe, pois no README deste repositório esses pontos estão especificados.

  ---

  ### Back-end

  O Back-end possui a seguinte estrutura:

  ```
  ├── README.md
  ├── index.js
  ├── data
  │  ├── dataset
  │  │  └── stranger-things-characters.json
  │  └── repository
  │     └── StrangerThings.js
  ├── services
  │  └── StrangerThings.js
  ├── package-lock.json
  └── package.json
  ```

  ---

  #### API

  A API consiste em um serviço simples com um endpoint `/` que retorna uma listagem com os personagens da série **Stranger Things**.

  ---

  #### Resposta

  A lista de personagem possui os seguintes campos:

  - **name**: Nome da personagem;

  - **status**: se a personagem está viva ou não na série. Os valores possíveis são `alive`, `deceased` ou `unknown`;

  - **origin**: o local de origem da personagem.

  A resposta é em formato `JSON`, e o retorno é sempre um array de objetos. Abaixo, um exemplo:

  ```JSON
  [
    {
      "name": "Will",
      "status": "Alive",
      "origin": "Byers Family"
    }
  ]
  ```

  ---

  #### Filtros

  Todos os campos da estrutura de retorno da resposta podem ser utilizados como filtros. Para isso, basta passar na `query string` o filtro desejado. No exemplo abaixo, estamos filtrando pelo _nome_ do personagem:

  > localhost:3000?name=el

  Os filtros são feitos utilizando uma `regex`, buscando pelo texto passado na `query string` em qualquer parte do campo, sem diferenciar maiúsculas de minúsculas.

  Nesse caso o retorno seria:

  ```JSON
  [
    {
      "name":"Russell",
      "status":"Alive",
      "origin":"Hawkings Middle School"
    },
    {
      "name":"Eleven",
      "status":"Alive",
      "origin":"Hopper Family"
    }
  ]
  ```

  ---

  #### Modo `upside down` (dw) - Back-end

  Na API, no arquivo `index.js`, há a seguinte variável de controle:

  ```javascript
  const hereIsTheUpsideDown = true;
  ```

  Caso ela seja `true`, a API ativará o modo "Mundo Invertido", conforme a série, e começará a responder desta forma:

  ```JSON
  [
    {
      "name":"llǝssnᴚ",
      "origin":"looɥɔS ǝlppᴉW sƃuᴉʞʍɐH",
      "status":"ǝʌᴉl∀"
    },
    {
      "name":"uǝʌǝlƎ",
      "origin":"ʎlᴉɯɐℲ ɹǝddoH",
      "status":"ǝʌᴉl∀"
    }
  ]
  ```

  ---

  ### Front-end

  O front-end consiste em um projeto simples utilizando React, que renderizará o seguinte layout:

  <img src="assets/frontend.png" width="800px" >

  Trata-se de um front-end bem simples que vai se comunicar com a nossa API. Ele possui as seguintes funcionalidades:

  - Uma tabela para exibição da resposta da nossa API;

  - Um campo de pesquisa para filtro de **nome**;

  - Botões de navegação para paginação;

  - Um botão para ativar o modo `Mundo Invertido` no front-end.

  Todas essas funcionalidades estão implementadas no componente `StrangerThings`.

  ---

  #### Comunicação com o back-end

  Na estrutura do projeto, temos um diretório `services`. Nesse diretório, há um arquivo `charactersAPI.js`, onde são feitas as chamadas `HTTP` para a nossa API, utilizando o `axios`.

  O service é uma classe que espera receber a URL da nossa API e um timeout para a requisição:

  ```javascript
  {
    url: 'localhost:3003',
    timeout: 30000
  }
  ```

  Esses parâmetros estão pré-programados de maneira fixa no componente (alteraremos esse comportamento durante o projeto):

  ```javascript
  const strangerThingsConfig = {
    url: 'localhost:3002',
    timeout: 30000,
  };

  const upsideDownConfig = {
    url: 'localhost:3003',
    timeout: 30000,
  };

  const charactersService = new CharactersService(strangerThingsConfig);
  const charactersUpsideDownService = new CharactersService(upsideDownConfig);
  ```

  ---

  #### Modo `upside down` (dw) - Front-end

  Assim como no back-end, o front-end também possui um modo "Mundo Invertido". Esse modo é ativado e desativado com o botão "Mudar de Realidade".

  A ideia é a seguinte: inicialmente, o front-end possui uma imagem de background e utiliza o service instanciado com a configuração contida na variável `strangerThingsConfig`. Ao ativar o Mundo Invertido, a imagem de background é alterada e passamos a utilizar o serviço instanciado com a configuração `upsideDownConfig`.

  Desse modo, ao "alternar entre os universos", vamos realizar chamadas a API's diferentes.

  No exemplo pré-programado, em um dos "universos", chamamos um serviço na porta `3002` e o outro serviço na porta `3003`. Exploraremos esse comportamento durante o projeto.

</details>

<details>
  <summary><strong>:convenience_store: Desenvolvimento </strong></summary><br />

  O código não está utilizando variáveis de ambiente. Você vai configurá-lo para utilizar essas variáveis, tornando parametrizáveis a porta e o _modo upside down_.

  Em seguida, você deverá adicionar todas as configurações necessárias para executar o `Docker` juntamente do `Heroku`.

  Você vai realizar o deploy do projeto (front-end e back-end) no _Heroku_. Você deverá realizar o deploy do projeto, conforme requisitos, no _Heroku_. Os comandos utilizados deverão ser adicionados no README.md de cada projeto. Para mais informações revisite o Course.

  Todos esses passos estão detalhados nos requisitos abaixo.

</details>

<details>
  <summary><strong>⚛️ Dica</strong></summary><br />
  Para publicar seu front-end React, utilize o buildpack [ mars/create-react-app ](https://elements.Heroku.com/buildpacks/mars/create-react-app-buildpack).

  Lembre-se de que é possível testar o comportamento definindo as variáveis de ambiente em sua máquina. Você pode fazer as variáveis apontarem tanto para o back-end, rodando localmente em sua máquina, quanto para as APIs já publicadas nos requisitos anteriores.

  ⚠️ **Dica: Lembre-se que ao importar uma variável de ambiente com `process.env.nomeDaVariavel`, seu tipo é `string`.** ⚠️
</details>

<details>
  <summary><strong>🗣 Nos dê feedbacks sobre o projeto!</strong></summary><br />

Ao finalizar e submeter o projeto, não se esqueça de avaliar sua experiência preenchendo o formulário. 
**Leva menos de 3 minutos!**

[FORMULÁRIO DE AVALIAÇÃO DE PROJETO](https://be-trybe.typeform.com/to/ZTeR4IbH)

:warning: **O avaliador automático não necessariamente avalia seu projeto na ordem em que os requisitos aparecem no readme. Isso acontece para deixar o processo de avaliação mais rápido. Então, não se assuste se isso acontecer, ok?**

</details>

<details>
  <summary><strong>🗂 Compartilhe seu portfólio!</strong></summary><br />

  Você sabia que o LinkedIn é a principal rede social profissional e compartilhar o seu aprendizado lá é muito importante para quem deseja construir uma carreira de sucesso? Compartilhe esse projeto no seu LinkedIn, marque o perfil da Trybe (@trybe) e mostre para a sua rede toda a sua evolução.

</details>

# Requisitos do projeto

⚠️ Lembre-se de que o seu projeto só será avaliado se estiver passando por **todos os _checks_** do **Linter**. Utilize o comando `npm run lint` no seu terminal para verificar os _checks_ do **Linter** 😉 ⚠️

Os requisitos estão agrupados por `frontend` e `backend`. Realize as alterações nos respectivos diretórios de cada repositório.

⚠️**IMPORTANTE**: Para esse projeto, as variáveis de ambiente devem ser definidas em um arquivo .env e o arquivo deve ser enviando no seu PR(Pull Request). ISSO NÃO É UMA PRÁTICA DE MERCADO, contexto no qual o arquivo .env deve ser sempre incluído no .gitignore, pois contém informações sensíveis. Aqui o arquivo .env será enviado apenas por motivo de avaliação.

---

## O teste no back-end:

### 1 - Verifica as variáveis de ambiente

<details>
  <summary>
    Altere o back-end para utilizar variáveis de ambiente para controlar a <b>porta</b> em que API escutará e o <b>modo</b> "upsideDown".
  </summary><br/>
  
  1. A porta que a API escutará, essa variável deve ter, necessariamente, o nome PORT e o seu valor deve ser 3000.

  2. O modo "upsideDown". Essa variável espera um valor boleano e deverá se chamar UPSIDEDOWN_MODE. Lembre-se de que as variáveis de ambiente são `strings`.
  O que será testado:
  - Se existe a variável de ambiente PORT;
  - Se a variável de ambiente UPSIDEDOWN_MODE existe e se ela é um boleano.

</details>

### 2 - Verifica se o arquivo Dockerfile está configurado da maneira correta

<details>
  <summary>
    O teste irá verificar se o arquivo `Dockerfile` existe e está configurado da maneira correta. Ele deve construir a imagem a partir da `node:14-alpine` e usar o comando `npm start` para iniciar a aplicação via `CMD`.
  </summary><br/>

  O que será testado:

  - Se o Dockerfile está utilizando a imagem `node:14-alpine`, verificando se as camadas dessa imagem estão incluídas no build que esse Dockerfile faz;

  - Se o Dockerfile usa `npm start` como `CMD`.

</details>

### 3 - Verifica se o arquivo heroku.yml está configurado na maneira correta

<details>
  <summary>
    Adicione e configure o arquivo <code>heroku.yml</code>.
  </summary><br/>

  1. O arquivo deve iniciar um servidor do tipo `web`;

  2. O `run` deve executar o servidor utilizando o `node`.

  Execute ambos na sua máquina para validar se o comportamento é o esperado.

  O que será testado:

    - Se o arquivo `heroku.yml` existe;

    - Se o serviço a ser executado é um serviço do tipo `web`;

    - Se o `node` é responsável por executar o servidor.

</details>

### 4 - Verifica action de Linter para ser executada no GitHub

<details>
  <summary>
    Você deverá criar uma <code>Action</code> para ser executada somente em **pull_requests** solicitados em todas as branches de seu repositório.
  </summary><br/>
  
  **Atenção**: O arquivo de configuração da action deverá ser criado em: `./actions/` com o nome `project.yml`.
  
  O que será validado:
  
  - Se o arquivo `project.yml` existe na pasta `actions`;
  
  - Se a Action será executada somente em pull requests;

  - Se o job foi nomeado como `eslint`;

  - Se o job `eslint` é executado com a versão **20.04** do ubuntu;

  - Se o primeiro passo do job `eslint` usa a action de **checkout**;
  
  - Se o segundo passo do job `eslint` usa a action de **setup-node** e sua versão é a `12`;

  - Se no terceiro passo do job o `eslint` executa a instalação das dependências;

  - Se o quarto passo do job `eslint` executa o pacote `eslint` via `npx`;


**Dica**: Dê uma olhada na [documentação de actions do github](https://docs.github.com/pt/actions/learn-github-actions/understanding-github-actions);

</details>

### 5 - Verifica o Deploy no Heroku

<details>
  <summary>
    Crie dois apps para a API: um para o o app <code>hawkins</code> e outro para o app <code>upside-down</code>.
  </summary><br/>

  ⚠️**IMPORTANTE**: Uma variável de ambiente com o nome `GITHUB_USER` deverá ser criada em seu `.env` com o **seu nome de pessoa usuária** do GitHub.

  ⚠️**IMPORTANTE**: 
 - O Heroku limita o tamanho do nome de uma aplicação para ter no máximo **30 caracteres** contendo apenas letras minúsculas:
    - se o seu nome de pessoa usuária do GitHub possuir mais do que **27 caracteres**, ou contenha **letras maiúsculas**, ou **comece com um número**, você não conseguirá criar uma aplicação com o nome no padrão solicitado pelo requisito. 
    - você pode usar uma abreviação do seu `GITHUB_USER` apenas com letras minúsculas na variável de ambiente e criar o `app` com o mesmo pré-fixo, por exemplo, temos o seguinte nome do github, `tryber-com-nome-de-github-maior-que-27-caracteres`:
```sh
GITHUB_USER=tryber
# E o nome dos apps deveriam ficariam assim:
# tryber-up - para o app hawkins;
# tryber-dw - para o app upside-down.
```


  1. Crie dois `apps` do Heroku a partir do mesmo código fonte (código da API). O nome do seu app no Heroku deverá conter o seu nome de pessoa usuária no GitHub seguido de "-up" e "-dw". Por exemplo, se seu nome de pessoa usuária no GitHub for "student", seus apps deverão ter os nomes "student-up" e "student-dw" e as URLs abaixo:

    - https://student-up.herokuapp.com/ - para o app hawkins;

    - https://student-dw.herokuapp.com/ - para o app upside-down.

  2. Configure a variável de ambiente criada para controlar o modo `UPSIDEDOWN`. Cada um dos `apps` deverá ter valores distintos, da seguinte maneira:

    - O app `hawkins` deverá ter o valor `false`;

    - O app `upside-down` deverá ter o valor `true`.

  3. Utilizando o `git`, faça o deploy de ambos os `apps` no Heroku.

  Acesse as URLs geradas e valide se ambas as API's estão no ar e funcionando como esperado.

  ⚠️ **IMPORTANTE**: As URLs deverão ser geradas pelo Heroku e não devem ser modificadas.

  **O que será testado**:
    - Se ao fazer uma requisição do tipo GET para o endpoint da API hawkins serão retornadas as informações corretas;

    - Se ao fazer uma requisição do tipo GET para o endpoint da API upside-down serão retornadas as informações corretas.
</details>

## O teste no front-end:

### 6 - Verifica as variáveis de ambiente do front-end

<details>
  <summary>
  Altere o front-end para utilizar variáveis de ambiente para controlar as <b>URLs</b> e <b>Timeouts</b> de comunicação com a API.
  </summary><br/>

  Perceba que o código está esperando por duas **APIs**. Uma para o modo `upside-down` e a outra para o modo normal.

  O nome das variáveis deve ser o seguinte:

  - Para seu back-end hawkins:
    - `REACT_APP_HAWKINS_URL` para a URL;

    - `REACT_APP_HAWKINS_TIMEOUT` para o timeout.

  - Para seu back-end UPSIDEDOWN:
    - `REACT_APP_UPSIDEDOWN_URL` para a URL;

    - `REACT_APP_UPSIDEDOWN_TIMEOUT` para o timeout.

  O que será testado:

  - Se existem as 4 variáveis de ambiente citadas acima.
</details>

### 7 - Verifica se foi feito o deploy do frontend no Heroku

<details>
  <summary>
  Faça o deploy do front-end.
  </summary><br/>

  ⚠️**IMPORTANTE**: Assim como no `Back-end`, a variável de ambiente `GITHUB_USER` deverá ser criada com o seu nome de pessoa usuária do GitHub.

  1. Crie um app do Heroku com o front-end. Vamos deixar o Heroku utilizar as configurações padrão. No momento de criar o app do Heroku, utilize o `buildpack` descrito abaixo, em **Dicas**;

  2. O nome do seu app no Heroku deve ser seu nome de pessoa usuária do GitHub seguido de "-ft". Por exemplo, se o seu nome de pessoa usuária do GitHub for "student", o nome do seu app será "student-ft" e a URL ***precisar ser*** https://student-ft.herokuapp.com/;

  2. Configure as variáveis de ambiente do app para apontar para as API's publicadas;

  3. Faça o deploy com o git.

  Para publicar seu front-end React, utilize o buildpack [mars/create-react-app](https://elements.Heroku.com/buildpacks/mars/create-react-app-buildpack).

  Lembre-se de que é possível testar o comportamento definindo as variáveis de ambiente em sua máquina. Você pode fazer as variáveis apontarem tanto para o back-end rodando localmente em sua máquina, quanto para as API's já publicadas nos requisitos anteriores.

  O que será testado:

    - Se ao visitar sua página no Heroku, o botão de mudar de realidade existe;

    - Se a pesquisa funciona como deveria, fazendo chamada a API externa;

    - Se o botão de mudar de realidade funciona;

    - Se os botões de próxima página e página anterior funcionam.  
</details>

## Bônus

### 8 - Verifica os multi-ambientes e modo de desenvolvimento.

<details>
  <summary>
    Utilize a estratégia de multi-ambientes no front-end.
  </summary><br/>

  Para isso:

  - Renomeie o remote atual para `remote-desenvolvimento`;
  
  - Crie e faça o deploy de um novo app no Heroku, conforme [requisito 7](#7---verifica-se-foi-feito-o-deploy-do-frontend-no-heroku). O nome do seu novo app no heroku deve ser seu nome de usuário do github seguido de "-pd" ("pd" se refere à "produção", ou seja, não está em desenvolvimento). Por exemplo, se o seu usuário do github for "student", o nome do seu app será "student-pd" e a url ***precisa ser*** https://student-pd.herokuapp.com/;
  
  - Adicione um elemento ao frontend que identifique que a aplicação está rodando em modo de "desenvolvimento". Esse elemento **deve** ser visível e conter o texto "Em desenvolvimento";
  
  - Lembre-se de criar uma variável de ambiente para controlar esse comportamento, configurando-a para ter um valor diferente em cada um dos ambientes publicados. Atente-se às regras de nomes para [váriáveis de ambiente utilizadas no React](https://create-react-app.dev/docs/adding-custom-environment-variables/).
  
  O que será testado:

  - Se ao acessar o front-end de desenvolvimento, haverá a tag com o texto "Em desenvolvimento";

  - Se ao acessar o front-end de produção, não haverá a tag.
</details>

---
-->
