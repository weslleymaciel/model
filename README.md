# Teste de Pré Seleção
> O objetivo deste teste é avaliar o perfil técnico do candidato mostrando uma prévia dos desafios que podem ser enfrentados em situações do dia a dia. A fim de criar um cenário realista estamos disponibilizando este repositório para que você possa desenvolver o desafio proposto submetendo suas PRs para revisão de nossa equipe técnica.


## Desafio

> Considere o seguinte cenário hipotético onde nosso cliente deseja desenvolver uma plataforma para coleta de dados corporativos de seus colaboradores a fim de criar uma base profissional dos envolvidos via preenchimento de um formulário WEB.
É de interesse do cliente que os colaboradores cadastrados na base recebam um e-mail contendo suas credenciais de acesso para que seja possível realizar a edição de seus dados cadastrais.
Para esta aplicação nosso cliente exige uma infraestrutura serverless altamente escalável com baixo custo. Nosso cliente já utiliza serviços AWS e sugeriu o uso de AWS Lambda a fim de manter sua arquitetura dentro de um mesmo contexto de trabalho.


## Lista de requisitos técnicos

* A aplicação deve implementar um CRUD utilizando Node.js com framework Express.
* Para utilização de recursos serverless da AWS recomendamos o uso de Serverless Framework com o plugin Serverless Offline para emular serviços como AWS Lambda.
* O banco de dados utilizado deve ser relacional e os dados devem ser manipulados via ORM, de preferência utilizar o Sequelize.
* O banco de dados possui informações pré-definidas pelo cliente que devem ser populadas através de arquivos seeders e a sua criação direcionada por arquivos migrations, a manipulação de dados diretamente na base para esta aplicação deve ser evitada.
* Dados sensíveis como IDs do banco de dados não devem trafegar de maneira exposta entre as requisições, para a proteção deste tipo de informação sugerimos o uso de padrão JSON Web Token para criptografar este tipo dado utilizando uma chave privada que deve ser armazenada no arquivo de ambiente da aplicação no servidor.
* Os formulários de entrada podem ser criados utilizando JavaScript, jQuery, Angular, React ou outra plataforma que o candidato se sinta familiarizado.

## Formulário de Acesso

* E-mail
* Senha
* Botão para realizar o primeiro cadastro


## Formulário de cadastro

* Foto de perfil (Upload de imagem com resolução máxima de 250px de largura por 250px de altura)
* Nome/Razão Social
* CPF/CNPJ
* Função/Cargo (Verificar dados pré-definidos)
* E-mail de acesso 
* Endereços (Verificar dados pré-definidos)
* Telefones (Verificar dados pré-definidos)
* Redes sociais (Verificar dados pré-definidos)


## Dados pré-definidos

### Tipos de cargos
* Programador front-end
* Programador back-end
* Designer
* Gerente de projetos

### Tipos de telefones
* Fixo
* Celular
* WhatsApp

### Tipos de redes sociais
* Facebook
* Instagram
* LinkedIn
* Pinterest


## Instalação

>Utilize este espaço para nos instruir de forma intuitiva a instalar recursos e executar procedimentos necessários para que sua aplicação seja reproduzida com sucesso.

## Casos de uso

>Utilize este espaço para nos apresentar sua aplicação, mostre casos de uso reais que possam nos ajudar a simular cenários e obter a melhor experiência com seu produto.

## Instruções de contribuição

1. Realize um fork do projeto (<https://github.com/easydotwork/backend-challenge/fork>)
1. Crie suas  branchs seguindo um formato padronizado. Exemplo "feature/0001-environment-settings"
2. Realize o commit de suas modificações 
3. Envie sua branch para nosso repositório
4. Crie um Pull Request de sua branch para que nossa equipe possa revisar
