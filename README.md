# :construction: README customizado em construção ! :construction:
<!-- O que vamos fazer?
A Fase A do projeto foi um sucesso! Sua equipe agora ficou responsável por expandir a aplicação e incluir algumas funcionalidades extra. Inclusive, vocês receberam uma base de código pronta que conseguiram adquirir de outra empresa, e que precisará ser testado.

Por que isso é importante?
Na vida de uma pessoa desenvolvedora é muito frequente a necessidade de trabalhamos com persistência de dados e com testes. Em primeiro lugar, este projeto te permitirá colocar em prática os conhecimentos sobre persistência com Spring Data e sobre testes que adquiriu durante a seção.

Mas para além disso, ele também te dará a oportunidade de exercitar suas habilidades na definição da arquitetura de um projeto. Este projeto foi desenvolvido focando no comportamento da sua aplicação, sem restringir tanto a forma com que ele será construído e implementado. Por isso, você terá maior liberdade (e responsabilidade) nas decisões de como estruturá-lo.

A capacidade de pensar e decidir como estruturar uma solução é algo muito valioso para uma pessoa programadora. Então vamos praticar!

Especificação
O que vamos avaliar?
Qualidade de código (“linter”)
Comportamento dos endpoints da API
Cobertura de código
O que devo desenvolver?
Neste projeto, verificamos se você é capaz de:

Aplicar o conhecimento do ecossistema Spring para criar rotas da API.
Aplicar a injeção de dependência para conectar as camadas de controle, serviço e persistência.
Utilizar o Spring Data JPA para implementar entidades e repositórios para a persistência em banco de dados, bem como implementar buscas customizadas.
Utilizar campos de data nas rotas da API e no banco de dados.
Criar testes unitários para garantir a qualidade e funcionamento correto da implementação, com cobertura de código adequada.
Atenção ⚠️: Leia o arquivo README.md do projeto com atenção para uma explicação detalhada de como desenvolver e entregar seu projeto.

Entregáveis
Para entregar o seu projeto, você deverá criar um Pull Request para um repositório no GitHub, seguindo as especificações detalhadas no README.md do projeto. Consulte o canal do Slack da turma para obter o endereço do repositório.

Combinados
Atente-se as instruções no README.md do repositório!
Qualquer dúvida, poste no Slack.
Lembre-se: você pode consultar nosso conteúdo sobre Git & GitHub na plataforma de aprendizagem quando quiser!
#VQV


# `Projeto Final - Agrix - Fase B`

Boas-vindas ao repositório do projeto `Projeto Final - Agrix - Fase B`

Para realizar o projeto, atente-se a cada passo descrito a seguir e se tiver **qualquer dúvida**,
nos envie no _Slack_ da turma! #vqv 🚀

Aqui, você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto a partir
desse repositório, utilizando uma branch específica e um _Pull Request_ para colocar seus códigos.

## Termos e acordos

Ao iniciar este projeto, você concorda com as diretrizes
do [Código de Conduta e do Manual da Pessoa Estudante da Trybe](https://app.betrybe.com/learn/student-manual/codigo-de-conduta-da-pessoa-estudante).

## Entregáveis

<details>
  <summary>🤷🏽‍♀️ Como entregar</summary><br />

Para entregar o seu projeto, você deverá criar um _Pull Request_ neste repositório.

Lembre-se que você pode consultar nosso conteúdo
sobre [Git & GitHub](https://app.betrybe.com/learn/course/5e938f69-6e32-43b3-9685-c936530fd326/module/fc998c60-386e-46bc-83ca-4269beb17e17/section/fe827a71-3222-4b4d-a66f-ed98e09961af/day/1a530297-e176-4c79-8ed9-291ae2950540/lesson/2b2edce7-9c49-4907-92a2-aa571f823b79)
e nosso [Blog - Git & GitHub](https://blog.betrybe.com/tecnologia/git-e-github/) sempre que
precisar!
</details>

<details>
  <summary>👨‍💻 O que deverá ser desenvolvido</summary><br />

A Fase A do projeto foi um sucesso! Sua equipe agora ficou responsável por expandir a aplicação e incluir algumas funcionalidades extra. Inclusive, vocês receberam uma base de código pronta que conseguiram adquirir de outra empresa, e que precisará ser testado.

Leia abaixo sobre as mudanças que ocorreram na arquitetura e mãos à obra! :)

</details>

<details>
  <summary><strong>📝 Habilidades a serem trabalhadas</strong></summary>

Neste projeto, verificamos se você é capaz de:

- Aplicar o conhecimento do ecossistema Spring para criar rotas da API.
- Aplicar a injeção de dependência para conectar as camadas de controle, serviço e persistência.
- Utilizar o Spring Data JPA para implementar entidades e repositórios para a persistência em banco
  de dados, bem como implementar buscas customizadas.
- Utilizar campos de data nas rotas da API e no banco de dados
- Criar testes unitários para garantir a qualidade e funcionamento correto da implementação, com
  cobertura de código adequada. 

</details>

<details>
<summary><strong>🗓 Data de Entrega</strong></summary>

- Este projeto é individual
- Serão `6` dias de projeto
- Data de entrega para avaliação regular do projeto: `30/08/2023 14:00`

</details>

## Orientações

<details>

   <summary><strong>‼ Antes de começar a desenvolver </strong></summary>

1. Clone o repositório

- Use o comando: `git clone <url do repositório>`
- Entre na pasta do repositório que você acabou de clonar:
    - `cd <nome do repositório>`

2. Instale as dependências

- `mvn install -DskipTests`

3. Crie uma branch a partir da branch `main`

- Verifique que você está na branch `main`
    - Exemplo: `git branch`
- Se você não estiver, mude para a branch `main`
    - Exemplo: `git checkout main`
- Agora, crie uma branch à qual você vai submeter os `commits` do seu projeto:
    - Você deve criar uma branch no seguinte formato: `nome-sobrenome-nome-do-projeto`;
    - Exemplo: `git checkout -b maria-soares-lessons-learned`

4. Crie na raiz do projeto os arquivos que você precisará desenvolver:

- Verifique que você está na raiz do projeto:
    - Exemplo: `pwd` -> o retorno vai ser algo tipo
      _/Users/maria/code/**sd-0x-project-lessons-learned**_
- Crie os arquivos index.html e style.css:
    - Exemplo: `touch index.html style.css`

5. Adicione as mudanças ao _stage_ do Git e faça um `commit`

- Verifique que as mudanças ainda não estão no _stage_:
    - Exemplo: `git status` (devem aparecer listados os novos arquivos em vermelho)
- Adicione o novo arquivo ao _stage_ do Git:
    - Exemplo:
        - `git add .` (adicionando todas as mudanças - _que estavam em vermelho_ - ao stage do Git)
        - `git status` (devem aparecer listados os arquivos em verde)
- Faça o `commit` inicial:
    - Exemplo:
        - `git commit -m 'iniciando o projeto. VAMOS COM TUDO :rocket:'` (fazendo o primeiro commit)
        - `git status` (deve aparecer uma mensagem tipo _nothing to commit_ )

6. Adicione a sua branch com o novo `commit` ao repositório remoto

- Usando o exemplo anterior: `git push -u origin maria-soares-lessons-learned`

7. Crie um novo `Pull Request` _(PR)_

- Vá até a página de _Pull Requests_
  do [repositório no GitHub](https://github.com/tryber/sd-0x-project-lessons-learned/pulls)
    - Clique no botão verde _"New pull request"_
    - Clique na caixa de seleção _"Compare"_ e escolha a sua branch **com atenção**
- Coloque um título para o seu _Pull Request_
    - Exemplo: _"Cria tela de busca"_
- Clique no botão verde _"Create pull request"_

- Adicione uma descrição para o _Pull Request_, um título nítido que o identifique, e clique no
  botão verde _"Create pull request"_

 <img width="1335" alt="Exemplo de pull request" src="https://user-images.githubusercontent.com/42356399/166255109-b95e6eb4-2503-45e5-8fb3-cf7caa0436e5.png">

- Volte até a [página de _Pull
  Requests_ do repositório](https://github.com/tryber/sd-0x-project-lessons-learned/pulls) e confira
  que o seu _Pull Request_ está criado

</details>

<details>

<summary><strong>⌨️ Durante o desenvolvimento</strong></summary>

Faça `commits` das alterações que você fizer no código regularmente, pois assim você garante
visibilidade para o time da Trybe e treina essa prática para o mercado de trabalho :) ;

- Lembre-se de sempre após um (ou alguns) `commits` atualizar o repositório remoto;
- Os comandos que você utilizará com mais frequência são:
    - `git status` _(para verificar o que está em vermelho - fora do stage - e o que está em verde -
      no stage)_;
    - `git add` _(para adicionar arquivos ao stage do Git)_;
    - `git commit` _(para criar um commit com os arquivos que estão no stage do Git)_;
    - `git push -u origin nome-da-branch` _(para enviar o commit para o repositório remoto na
      primeira vez que fizer o `push` de uma nova branch)_;
    - `git push` _(para enviar o commit para o repositório remoto após o passo anterior)_.

</details>

<details>
<summary><strong>🎛 Checkstyle</strong></summary>

Para garantir a qualidade do código, vamos utilizar neste projeto o `Checkstyle`. Assim o código
estará alinhado com as boas práticas de desenvolvimento, sendo mais legível e de fácil manutenção!
Para poder rodar o `Checkstyle` certifique-se de ter executado o comando `mvn install` dentro do
repositório.

Para rodá-los localmente no repositório, execute os comandos abaixo:

```bash
mvn checkstyle:check
```

Se a análise do `Checkstyle` encontrar problemas no seu código, tais problemas serão mostrados no
seu terminal. Se não houver problema no seu código, nada será impresso no seu terminal.

Você pode também instalar o plugin do `Checkstyle` na sua `IDE`. Para isso, volte na primeira seção
do conteúdo.

⚠️ **PULL REQUESTS COM ISSUES NO `Checkstyle` NÃO SERÃO AVALIADAS. ATENTE-SE PARA RESOLVÊ-LAS ANTES
DE FINALIZAR O DESENVOLVIMENTO!** ⚠️

</details>

<details>
<summary><strong>🛠 Testes</strong></summary>

Para executar todos os testes basta rodar o comando:

```bash
mvn test
```

Para executar apenas uma classe de testes:

```bash
mvn test -Dtest="TestClassName"
```

</details>

## Especificações do projeto

<details>
<summary> ⚠️ Informações sobre como implementar os requisitos</summary><br>

Os testes deste projeto são, de maneira geral, testes de integração. Cada teste fará diversas chamadas à sua API e validará a resposta e o comportamento da aplicação, mas sem restringir implementações específicas de classes e métodos.

Por isso, neste projeto você terá maior liberdade para estruturar e implementar sua aplicação da forma que escolher, desde que atenda aos requisitos pedidos e algumas especificações que serão explicadas aqui.

Uma das restrições é que o projeto deve ser implementado utilizando o ecossistema Spring (Spring Boot, Spring Web, Spring Data, etc). Você pode utilizar outras bibliotecas e ferramentas se desejar, mas garanta que elas são compatíveis com o Spring e com os testes do projeto.
</details>

<details>
<summary>🗄️ Descrição do banco de dados</summary><br>

Na Fase A do projeto o banco de dados foi definido como abaixo:

![Modelo de tabelas](images/agrix-tabelas-fase-a.png)

No entanto, agora a aplicação precisará ser ampliada. Este é o diagrama atualizado:

![Modelo de tabelas](images/agrix-tabelas-fase-b.png)

Nesse modelos, temos as seguintes tabelas:
- `farm`: representa uma fazenda
- `crop`: representa uma plantação, e está em relacionamento `n:1` ("muitos para um") com a tabela `farm`
  - Esta tabela recebeu alguns campos a mais, que guardam datas, e que precisarão ser considerados durante o desenvolvimento da Fase B.
- `fertilizer`: esta nova tabela representa um fertilizante, e está em um relacionamento `n:n` ("muitos para muitos") com a tabela `crop`. Esse relacionamento é realizado através da tabela `crop_fertilizer`.

Alguns elementos importantes a considerar sobre a implementação da camada de persistência e do banco de dados:
- Apesar do nome das tabelas e colunas (com seus tipos) não precisarem ser exatamente esses, os testes do projeto chamarão sua API usando requisições e esperam respostas baseados nesse modelo.
- Os testes do projeto não esperam um banco de dados específico. No entanto, sugerimos que você utilize o MySQL como banco de dados.
- Os testes do projeto utilizam um banco "mockado" em memória do tipo H2. Isso não deve afetar sua implementação, mas tome cuidado ao utilizar funcionalidades muito específicas de um determinado tipo de banco de dados e que não sejam compatíveis com os testes.
</details>

<details>
<summary>🏛️ Arquitetuda da aplicação</summary><br>

Como dito, neste projeto você terá maior liberdade para escolher como vai estruturar e implementar sua aplicação. Algumas dicas e recomendações:

- O projeto não possui uma estrutura pré-definida de pacotes (com algumas exceções). Ainda assim, recomendamos que você cuide para ter uma boa organização e divisão de pacotes. Na dúvida, se inspire no que você viu no conteúdo ou nos projetos anteriores.
- Da mesma maneira, não há exigência de uma arquitetura específica de camadas. No entanto, uma boa arquitetura pode ajudar a garantir não só uma maior qualidade de código, como também facilitar para você realizar manutenção e aprimoramentos posteriormente.
- Sugerimos que você considere utilizar os padrões e boas práticas que tem visto no conteúdo, aulas e projetos. Mas sinta-se à vontade também para estudar e pensar em como pode melhorar e expandir a forma com que estrutura seu código.

Por fim, a mensagem que deixamos é: aproveite a oportunidade para desenvolver mais sua capacidade de estruturar e construir uma aplicação!

</details>

## Requisitos

### 1. Migre seu código da Fase A para este projeto (Fase B)

<details>
  <summary>Migre seu código que implementou no "Agrix - Fase A" para este projeto (Fase B)</summary><br />

Neste requisito, você deverá trazer todo o código que você implementou durante o "Agrix - Fase A" para este projeto (Agrix - Fase B).

Tome cuidado especial com:
 - `pom.xml`: o `pom.xml` inicial das Fase B não é igual ao `pom.xml` da Fase A, então você não pode simplesmente substituílo. Cuide para transferir apenas as dependências que você incluiu, sem alterar as outras configurações do projeto.
 - Agora na Fase B já disponibilizamos um pacote com código que você utilizará em um dos requisitos abaixo. Tome cuidado também para não mover nem apagar esse código.

Durante os testes deste requisito, apenas a rota POST `/farms` será validada. No entanto, você precisará trazer todo o código que você implementou na fase anterior.

<details>
  <summary>🔍 Formato/exemplo de requisição e resposta</summary><br />

Exemplo de requisição para a rota POST `/farms`:
```json
{
  "name": "Fazendinha",
  "size": 5
}
```

Exemplo de resposta:

```json
{
  "id": 1,
  "name": "Fazendinha",
  "size": 5
}
```
</details>

</details>


### 2. Escreva testes com cobertura mínima de 80% das linhas da classe PersonService

<details>
  <summary>Escreva testes com cobertura mínima de 80% das linhas da classe PersonService</summary><br />

A Fase A do projeto Agrix deu tão certo que as pessoas inverstidoras decidiram comprar uma base de código existente de outra empresa. Infelizmente, esse código não incluia testes unitários, e você ficou responsável por escrever testes para uma das classes.

O código adquirido está no pacote `com.betrybe.agrix.ebytr.staff`. Por enquanto o código não será refatorado ou integrado à aplicação, então tome cuidado para não alterar ou apagar nada nesse pacote.

A classe que você deverá testar é a `PersonService`, dentro do subpacote `service`. Você deverá garantir uma cobertura dos testes de no mínimo **80%** das linhas dessa classe. Crie seus testes no pacote `com.betrybe.agrix.solution`.

**_Atenção_**: Você pode utilizar as funcionalidades de cobertura de código da sua IDE para te ajudar a identificar o que falta testar. No entanto, lembre-se de que a cobertura que será considerada é a dada pelos testes oficiais do projeto.

</details>

### 3. Ajuste (ou crie) a rota POST /farms/{farmId}/crops para utilizar datas

<details>
  <summary>Ajuste ou crie a rota POST /farms/{farmId}/crops para utilizar campos com datas</summary><br />

Neste requisito, você deverá garantir que a rota para criação de plantações tenha os campos com data definidos abaixo. 

Caso você já tenha implementado esta rota durante a Fase A do projeto, você precisa ajustá-la para incluir os novos campos. Caso contrário, você precisará implementar a rota completa, incluindo os campos antigos e os novos.

A definição original da rota é:
- `/farms/{farmId}/crops` (`POST`)
    - deve receber o `id` da fazenda pelo caminho da rota (representado aqui por `farmId` apenas para diferenciar da plantação)
    - deve receber via corpo do POST os dados da plantação (veja abaixo para os dados de requisição
      e resposta)
    - deve salvar a nova plantação a partir dos dados recebidos, associada à fazenda com o ID
      recebido
    - em caso de sucesso, deve:
        - retornar o status HTTP 201 (CREATED)
        - retornar os dados da plantação criada. A resposta deve incluir o `id` da plantação e
          o `id` da fazenda, mas não deve incluir os dados da fazenda.
    - caso não exista uma fazenda com o `id` passado, a rota deve retornar o status HTTP 404 com a
      mensagem `Fazenda não encontrada!` no corpo da resposta.

Você precisará incluir dois atributos novos (descritos no diagrama atualizado das tabelas):
- `plantedDate`, representando a data em que a plantação foi semeada
- `harvestDate`, representando a data em qua a plantação foi ou está prevista para ser colhida

As datas devem ser recebidas e retornadas no formato ISO (`YYYY-MM-DD`). Sugerimos que você use o tipo `LocalDate`.

Nota: dependendo de como você fez sua implementação, é possível que ao resolver este requisito você também resolva automaticamente os próximos requisitos relacionados a plantações. Caso isso aconteça, não se assuste :)

<details>
  <summary>🔍 Formato/exemplo de requisição e resposta</summary><br />

Exemplo de requisição na rota `/farms/1/crops` (supondo que exista uma fazenda com `id = 1`):

```json
{
  "name": "Couve-flor",
  "plantedArea": 5.43,
  "plantedDate": "2022-12-05",
  "harvestDate": "2023-06-08"
}
```

Exemplo de resposta:

```json
{
  "id": 1,
  "name": "Couve-flor",
  "plantedArea": 5.43,
  "plantedDate": "2022-12-05",
  "harvestDate": "2023-06-08",
  "farmId": 1
}
```

Note que o `id` da resposta se refere à plantação, e que o da fazenda está em `farmId`.

</details>

</details>

### 4. Ajuste (ou crie) a rota GET /farms/{farmId}/crops para utilizar datas

<details>
  <summary>Ajuste ou crie a rota GET /farms/{farmId}/crops para utilizar campos com datas</summary><br />

Da mesma forma que no requisito 2, você deve incluir os campos com datas na resposta deste requisito.

A definição original da rota é:
- `/farms/{farmId}/crops` (`GET`):
    - deve receber o `id` de uma fazenda pelo caminho
    - deve retornar uma lista com todas as plantações associadas à fazenda
    - caso não exista uma fazenda com esse `id`, a rota retornar o status HTTP 404 com a
      mensagem `Fazenda não encontrada!` no corpo da resposta.

Os campos novos a serem incluídos são os mesmos do requisito anterior.

<details>
  <summary>🔍 Formato/exemplo de resposta</summary><br />

Exemplo de resposta para a rota `/farms/1/crops` (supondo que exista uma fazenda com `id = 1`):

```json
[
  {
    "id": 1,
    "name": "Couve-flor",
    "plantedArea": 5.43,
    "plantedDate": "2022-12-05",
    "harvestDate": "2023-06-08",
    "farmId": 1
  },
  {
    "id": 2,
    "name": "Alface",
    "plantedArea": 21.3,
    "plantedDate": "2022-02-15",
    "harvestDate": "2023-02-20",
    "farmId": 1
  }
]
```

</details>

</details>

### 5. Ajuste (ou crie) a rota GET /crops para utilizar datas

<details>
  <summary>Ajuste ou crie a rota GET /crops para utilizar campos com datas</summary><br />

A definição original da rota é:
- `/crops` (`GET`)
    - deve retornar uma lista de todas as plantações cadastradas. A resposta deve incluir o `id` de
      cada plantação e o `id` da fazenda associada, mas não deve incluir os dados da fazenda.

Os campos novos a serem incluídos são os mesmos do requisito anterior.

<details>
  <summary>🔍 Formato/exemplo de resposta</summary><br />

```json
[
  {
    "id": 1,
    "name": "Couve-flor",
    "plantedArea": 5.43,
    "plantedDate": "2022-02-15",
    "harvestDate": "2023-02-20",
    "farmId": 1
  },
  {
    "id": 2,
    "name": "Alface",
    "plantedArea": 21.3,
    "plantedDate": "2022-02-15",
    "harvestDate": "2023-02-20",
    "farmId": 1
  },
  {
    "id": 3,
    "name": "Tomate",
    "plantedArea": 1.9,
    "plantedDate": "2023-05-22",
    "harvestDate": "2024-01-10",
    "farmId": 2
  }
]
```

</details>

</details>

### 6. Ajuste (ou crie) a rota GET /crops/{id} para utilizar datas

<details>
  <summary>Ajuste ou crie a rota GET /crops/{id} para utilizar campos com datas</summary><br />

A definição original da rota é:
- `/crops/{id}` (`GET`):
    - deve receber o `id` de uma plantação pelo caminho da rota
    - caso exista a plantação com o `id` recebido, deve retornar os dados da plantação. A resposta
      deve incluir o `id` de cada plantação e o `id` da fazenda associada, mas não deve incluir os
      dados da fazenda.
    - caso não exista uma plantação com o `id` passado, a rota deve retornar o status HTTP 404 com a
      mensagem `Plantação não encontrada!` no corpo da resposta.

Os campos novos a serem incluídos são os mesmos do requisito anterior.

<details>
  <summary>🔍 Formato/exemplo de resposta</summary><br />

Exemplo de resposta para a rota `/crops/3` (supondo que exista uma plantação com `id = 3`:

```json
{
  "id": 3,
  "name": "Tomate",
  "plantedArea": 1.9,
  "plantedDate": "2023-05-22",
  "harvestDate": "2024-01-10",
  "farmId": 2
}
```

</details>

</details>


### 7. Crie a rota GET /crops/search para busca de plantações

<details>
  <summary>Crie a rota GET /crops/search para busca de plantações a partir da data de colheita</summary><br />

A rota a ser criada é:
- `/crops/search` (`GET`)
  - deve receber dois parâmetros por query string para busca:
    - `start`: data de início
    - `end`: data de fim
  - deve retornar uma lista com as plantações nas quais o campo `harvestDate` esteja entre as data de início e de fim.
    - a comparação das datas deve ser inclusiva (ou seja, deve incluir datas que sejam iguais à de início ou à de fim)
  - a resposta deve incluir o `id` de cada plantação e o `id` da fazenda associada, mas não deve incluir os dados da fazenda.

<details>
  <summary>🔍 Formato/exemplo de resposta</summary><br />

Exemplo de resposta para a rota `/crops/search?start=2023-01-07&end=2024-01-10`:

```json
[
  {
    "id": 1,
    "name": "Couve-flor",
    "plantedArea": 5.43,
    "plantedDate": "2022-02-15",
    "harvestDate": "2023-02-20",
    "farmId": 1
  },
  {
    "id": 3,
    "name": "Tomate",
    "plantedArea": 1.9,
    "plantedDate": "2023-05-22",
    "harvestDate": "2024-01-10",
    "farmId": 2
  }
]
```

</details>

</details>


### 8. Crie a rota POST /fertilizers

<details>
  <summary>Crie a rota POST /fertilizers para criação de um novo fertilizante</summary><br />

Neste requisito, você deverá criar a primeira rota para gerenciamento de fertilizantes. 

Lembre-se que os fertilizantes estão em um relacionamento `n:n` com plantações, então considere isso na hora de implementar sua solução deste e dos próximos requisitos.

A rota a ser criada é:
- `/fertilizers` (`POST`)
    - deve receber via corpo do POST os dados de um fertilizante
    - deve salvar um novo fertilizante a partir dos dados recebidos
    - em caso de sucesso, deve:
        - retornar o status HTTP 201 (CREATED)
        - retornar os dados do fertilizante criado, incluindo seu `id`

<details>
  <summary>🔍 Formato/exemplo de requisição e resposta</summary><br />

Exemplo de requisição:

```json
{
  "name": "Compostagem",
  "brand": "Feita em casa",
  "composition": "Restos de alimentos"
}
```

Exemplo de resposta:

```json
{
  "id": 1,
  "name": "Compostagem",
  "brand": "Feita em casa",
  "composition": "Restos de alimentos"
}
```

</details>

</details>


### 9. Crie a rota GET /fertilizers

<details>
  <summary>Crie a rota GET /fertilizers para listar todos os fertilizantes cadastrados</summary><br />

Neste requisito, você deverá criar a rota para listar todos os fertilizantes cadastrados. A rota a ser criada é:
- `/fertilizers` (`GET`):
    - deve retornar uma lista de todos os fertilizantes cadastrados, incluindo o `id` de cada.

<details>
  <summary>🔍 Formato/exemplo de resposta</summary><br />

```json
[
  {
    "id": 1,
    "name": "Compostagem",
    "brand": "Feita em casa",
    "composition": "Restos de alimentos"
  },
  {
    "id": 2,
    "name": "Húmus",
    "brand": "Feito pelas minhocas",
    "composition": "Muitos nutrientes"
  },
  {
    "id": 3,
    "name": "Adubo",
    "brand": "Feito pelas vaquinhas",
    "composition": "Esterco"
  }
]
```
</details>

</details>


### 10. Crie a rota GET /fertilizers/{id}

<details>
  <summary>Crie a rota GET /fertilizers/{id} para pegar as informações de um fertilizante</summary><br />

Neste requisito, você deverá criar a rota para pegar as informações de um fertilizante. A rota a ser criada é:
- `/fertilizers/{fertilizerId}` (`GET`):
    - deve receber o `id` de um fertilizante pelo caminho da rota
    - caso exista o fertilizante com o `id` recebido, deve retornar seus dados, incluindo seu `id`
    - caso não exista um fertilizante com o `id` passado, a rota deve retornar o status HTTP 404 com a
      mensagem `Fertilizante não encontrado!` no corpo da resposta.

<details>
  <summary>🔍 Formato/exemplo de resposta</summary><br />

Exemplo de resposta da rota `/fertilizers/3` (supondo que exista um fertilizante com `id = 3`):

```json
{
  "id": 3,
  "name": "Adubo",
  "brand": "Feito pelas vaquinhas",
  "composition": "Esterco"
}
```

</details>

</details>


### 11. Crie a rota POST /crops/{cropId}/fertilizers/{fertilizerId}

<details>
  <summary>Crie a rota POST /crops/{cropId}/fertilizers/{fertilizerId} associar uma plantação com um fertilizante</summary><br />

Neste requisito, você deverá criar a rota para criar a associação entre uma plantação e um fertilizante. A rota a ser criada é:
- `/crops/{cropId}/fertilizers/{fertilizerId}` (`POST`)
    - deve receber tanto o `id` da plantação quanto o `id` do fertilizante pelo caminho da rota
    - o corpo da requisição será vazio
    - deve fazer a associação entre o fertilizante e a plantação
    - em caso de sucesso, deve retornar o status HTTP 201 (CREATED) com a mensagem `Fertilizante e plantação associados com sucesso!` no corpo da resposta
    - caso não exista uma plantação com o `id` recebido, a rota deve retornar o status HTTP 404 com a mensagem `Plantação não encontrada!` no corpo da resposta.
    - caso não exista um fertilizante com o `id` recebido, a rota deve retornar o status HTTP 404 com a mensagem `Fertilizante não encontrado!` no corpo da resposta.

<details>
  <summary>🔍 Formato/exemplo de requisição e resposta</summary><br />

Exemplo de resposta para a rota `/crops/1/fertilizers/2` (supondo que exista uma plantação com `id = 1` e um fertilizante com `id = 2`):

```text
Fertilizante e plantação associados com sucesso!
```

</details>

</details>


### 12. Crie a rota GET /crops/{cropId}/fertilizers

<details>
  <summary>Crie a rota GET /crops/{cropId}/fertilizers para listar os fertilizante associados a uma plantação</summary><br />

Neste requisito, você deverá criar a rota para listar os fertilizante associados a uma plantação. A rota a ser criada é:
- `/crops/{cropId}/fertilizers` (`GET`):
    - deve receber o `id` de uma plantação pelo caminho
    - deve retornar uma lista com todas os fertilizantes associados à plantação
    - caso não exista uma plantação com o `id` recebido, a rota deve retornar o status HTTP 404 com a mensagem `Plantação não encontrada!` no corpo da resposta.

<details>
  <summary>🔍 Formato/exemplo de resposta</summary><br />

Exemplo de resposta para a rota `/crops/2/fertilizers` (supondo que exista uma plantação com `id = 2`):

```json
[
  {
    "id": 2,
    "name": "Húmus",
    "brand": "Feito pelas minhocas",
    "composition": "Muitos nutrientes"
  },
  {
    "id": 3,
    "name": "Adubo",
    "brand": "Feito pelas vaquinhas",
    "composition": "Esterco"
  }
]
```

</details>

</details>

---

<details>
<summary><strong>🗣 Nos dê feedbacks sobre o projeto!</strong></summary>

Ao finalizar e submeter o projeto, não se esqueça de avaliar sua experiência preenchendo o
formulário.
**Leva menos de 3 minutos!**

[Formulário de avaliação do projeto](https://be-trybe.typeform.com/to/ZTeR4IbH#cohort_hidden=CH26-JAVA&template=betrybe/java-0x-projeto-final-agrix-fase-b)

</details>

<details>
<summary><strong>🗂 Compartilhe seu portfólio!</strong></summary>

Você sabia que o LinkedIn é a principal rede social profissional e compartilhar o seu aprendizado lá
é muito importante para quem deseja construir uma carreira de sucesso? Compartilhe esse projeto no
seu LinkedIn, marque o perfil da Trybe (@trybe) e mostre para a sua rede toda a sua evolução.

</details>

---

<!-- mdi versão 1.1 projeto ⚠️ não exclua esse comentário -->



-->
