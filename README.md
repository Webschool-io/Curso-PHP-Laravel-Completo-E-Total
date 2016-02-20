# Curso-PHP-Laravel-Completo-E-Total
Curso mais completo e gratuito de Laravel do Universo aqui do Brasil.

Professor: [Michael Douglas](https://github.com/michaeldouglas/)

## Ementa

- O que é necessário saber
  - Iniciando sua vida com serviços
    - Pretendo ensinar sobre o que é REST como o Laravel implementa isso em sua arquitetura. E também o por que de ser o primeiro item do curso já que estamos falando Laravel ! 
  - Json
Item reservado para explicar um pouco sobre o que é Json.
  - Composer
Irei ensinar os comandos básicos do composer e também como instalar o Laravel via: Composer e Laravel Installer
  - NameSpace
Explicação básica do que é e também como utilizar tanto em Laravel quanto PHP puro.
Configurando os servidores WEB Apache e Nginx
Irei demonstrar a instalação dos servidores Web e também a configuração do Laravel nos ambientes.
- Arquitetura Laravel
  - Estrutura
Explicação da estrutura e organização de pastas no ambiente Laravel
  - MVC Laravel
Como funciona o MVC dentro do ambiente Laravel e explicar o por que da não existência da pasta: Model
  - Configuração de ambiente “.env”
Explicação do que é uma variável de ambiente e também sobre a utilização da biblioteca DotEnv.
- Começando meu mundo em Laravel
  - Rotas
    - Rotas básicas
Aqui mais uma explicação inicial de como é a criação de rotas no Laravel
    - Rotas com parâmetros
Explicação de passagem de parâmetros para rotas e como deixa-los  obrigatórios e também opcionais.
  - Grupo de rotas
Middleware
Explicação do que um Middleware e também criação dos nossos próprios Middlewars. - E implementação em nossa rota
Namespaces
Chamando o NameSpace para chegada no controller.
  - Controladores
    - O básico dos controladores
        Explicação de como criar nossos controladores para o Laravel.
    - Controladores RESTfull
        Criando um controlador no padrão RestFull
    - Controladores implícitos
        Criando um controlador implícito
  - Respostas HTTP
    - Respostas em JSON
      Json simples como retorno de rota
      Jsonp como retorno de rota
    - Macro respostas
      Explicação do que é a Macro resposta no Laravel.
  - Views
    - View
        O básico do que é uma View na camada Laravel e como são implementadas.
    - Fornecendo dados para o HTML
        Utilizando os dados criados no controlar e fornecendo para a View.
  - Blade
    - O que é template engine ?
    - Layouts Laravel
        Criando nosso primeiro layout
        Extendendo nosso layout
  - View Composers  
  - Validação
    - Utilizando validadores nos padrões do Laravel
        Irei explicar além do que são também como estender a funcionalidade e utilizar a sobrescrita para criar seu validador.
    - Criando nossos validadores
  - Migrations
    - O que são ?
    - Criando nossas migrations
        Pretendo criar as tabelas a partir do esquema de migração do Laravel.
    - Executando nossas migrations
  - Eloquent ORM
    - Criando os primeiros modelos
    - Leitura de dados
    - Atualização de dados
    - Removendo registros
    - Edição de dados
    - Relacionamento de tabelas
  - Autenticação
    - Utilizando o padrão Auth Laravel
  - Teste unitário Laravel
    - O básico que você deve saber antes de iniciar
    - Aplicando testes com Laravel
    - Model Factories
        Além de utilizar irei realizar testes utilizando o modelo.
- DDD - Domain Driven Development. [Vinicius Reis](https://github.com/vinicius73)
    - Introdução
      - Módulos. O que são, o que resolvem e o eu não resolvem. 
      - Um pouco de S.O.L.I.D.
    - Afinal o que é "desenvolvimento orientado a dominíos"?
      - Core
      - Domains (Dominíos)
      - Applications (Aplicações)
      - Support (Suporte)
    - O que saber antes de se aventurar
      - Service Provider
      - Service Container
      - Dependency Injection
    - Direto ao código
      - Criando o "core"
      - Criando nossos dominíos
      - Criando nossas aplicações
      - Criando pacotes de suporte
    - Mergulhando fundo
      - Repository Partten
      - Services
