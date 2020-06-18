# Teste de Pré Seleção
> O objetivo deste teste é avaliar o perfil técnico do candidato mostrando uma prévia dos desafios que podem ser enfrentados em situações do dia a dia. A fim de criar um cenário realista estamos disponibilizando este repositório para que você possa desenvolver o desafio proposto submetendo suas PRs para revisão de nossa equipe técnica.

## Desafio

Considere o seguinte cenário hipotético onde nosso cliente deseja desenvolver uma plataforma para coleta de dados corporativos de seus colaboradores a fim de criar uma base profissional dos envolvidos via preenchimento de um formulário WEB.
É de interesse do cliente que os colaboradores cadastrados na base recebam um e-mail informativo contendo um check list de suas tarefas com base em sua função dentro da empresa logo após o cadastro.
Para esta aplicação nosso cliente exige uma infra estrutura serverless altamente escalável com baixo custo. Nosso cliente já utiliza serviçoes AWS e sugeriu o uso de AWS Lambda a fim de manter sua arquitetura dentro de um mesmo contexto de trabalho.

## Lista de requisitos técnicos

* A aplicação deve ser implementada utilizando Node.js com framework Express.
* Para utilização de recursos serverless da AWS recomendamos o uso de Serverless Framework com o plugin Serverless Offline para emular serviços como AWS Lambda.
* O banco de dados utilizado deve ser relacional e os dados devem ser manipulados via ORM, de preferência utilizar o Sequelize.
* O banco de dados possui informações pré definidas pelo cliente que devem ser populadas através de arquivos seeders e a sua criação direcionada por arquivos migrations, a manipulação de dados diretamente na base para esta aplicação deve ser evitada.

## Instalação

>Utilize este espaço para nos instruir de forma intuitiva a instalar recursos e executar procedimentos necessários para que sua aplicação seja reproduzida com sucesso em nossos compudatores.

## Casos de uso

>Utilize este espaço para nos apresentar sua aplicação, mostre casos de uso reais que possam nos ajudar a simular cenários e obter a melhor experiência com seu produto.

## Instruções de contribuição

1. Crie suas  branchs seguindo um formato padronizado. Exemplo (`git checkout -b feature/0001-environment-settings`)
2. 
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
