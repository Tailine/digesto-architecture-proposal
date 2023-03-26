# Proposta arquitetura Digesto

Esse projeto consite em uma proposta de arquitetura de uma aplicação frontend escrita em React para a aplicação Digesto.

## Estrutura de pastas

Aplicação composta pelas seguintes pastas:

- `src`
  - `components`: componentes mais genéricos
  - `config`: arquivos de configuração
  - `hooks`
  - `layouts`: estrutura de páginas
  - `pages`: além da página pode conter componentes específicos desta página
  - `ports`: interfaces de comunicação com o meio externo
  - `services`: chamadas para api
  - `adapters`: implementa as interfaces definidas na pasta `ports`
  - `types`: tipos de dados
  - `utils`: funções que podem ser reaproveitadas
  - `e2e`: testes end-to-end

## Componentização

![screenshot da página destacando os componentes](digesto.png)

<span style="color:red">#</span> AuthLayout <br>
<span style="color:purple">#</span> Header <br>
<span style="color:green">#</span> SidebarMenu <br>
<span style="color:blue">#</span> MainLayout <br>
