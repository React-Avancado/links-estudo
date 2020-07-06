# Glossário
Conteúdo que pode servir de consulta caso você precise ou esqueça o que algum termo significa ou o para que alguma tecnologia serve.

### Termos
Alguns termos utilizados ao longo do curso.

#### O que é um CMS Headless?
Um [CMS Headless](https://headlesscms.org/) é igual qualquer CMS que você conheça (como WordPress, por exemplo). A diferença é que ele não é responsável por entregar a interface do seu conteúdo final (blog, site) e apenas gerencia o conteúdo disponibilizando uma API para que você consuma os dados da maneira que for mais conveniente. Desacoplando, dessa forma, seu front-end da sua camada de dados.

#### O que é TDD?
TDD (desenvolvimento guiado à testes ou test-driven development) é uma cultura e uma forma de desenvolvimento de software, guiada por testes. É marcada por 3 momentos específicos chamados: red-green-refactor.

Ao utilizar TDD a ideia é que você comece desenvolvendo seus testes antes de tocar qualquer linha de código do seu produto final. Dessa forma, você escreve um teste que sabe que será falho (red), depois realiza o desenvolvimento necessário apenas para que seus testes passem (green) e, por fim, refatora seus código para que seja reutilizável o suficiente e continue com os testes passando (refactor).

#### O que é um Framework?
Um framework é uma ferramenta que permeia a forma como você se organiza e desenvolve. Geralmente traz algumas estruturas, definições e ferramentas prontas, para que seu trabalho seja focado em desenvolver o seu produto e não somente lidar com questões técnicas sobre linguagens e tecnologias.

#### O que é SSR (_server-side rendering_ ou renderização do lado do servidor)?
Como o próprio nome entrega, é uma estrutura de renderização onde seu conteúdo é previamente renderizado no servidor, retornando ao cliente (como o navegador) uma estrutura de informações (HTML e a aplicação em si) já prontas para serem consumidas.

#### O que é CSR (_client-side rendering_ ou renderização do lado do cliente)?
Diferente do SSR, é uma estrutura onde a criação e renderização da aplicação é responsabilidade do cliente (como o navegador) e não do servidor.

#### O que é SSG (_static site generation_ ou geração de site estático)?
Diferente do SSR e do CSR, utilizar conteúdo estático é uma abordagem onde todo seu conteúdo será disponibilizado única e exclusivamente via arquivos estáticos (HTML/CSS/JS). Dessa maneira, seu cliente (como o navegador) consumirá o conteúdo final já renderizado e formatado, mas não poderá ter atualizações de servidor caso algum dado dinâmico seja atualizado (o que dependeria de uma rotina de build).

---

### Stack
Uma breve explicação sobre todas as tecnologias utilizadas.

#### O que é React?
[React](https://reactjs.org/) é uma biblioteca criada pelo time do Facebook, para desenvolvimento de interfaces, que leva como premissa a criação de componentes reutilizáveis.

#### O que é TypeScript?
[TypeScript](https://www.typescriptlang.org/) é um superset de JavaScript. Isso quer dizer que é uma ferramenta que atua como uma extensão do JS, possibilitando que você utilize, além de tipagem estática (coisa que não existe na linguagem por si só), outras diversas funcionalidades.

#### O que é NextJS?
[NextJS](https://nextjs.org/) é um Framework baseado em React, que traz consigo uma estrutura pronta de pastas, páginas e de ferramentas para build. 

#### O que é Strapi?
[Strapi](https://strapi.io/) é um CMS Headless completamente customizável.

#### O que é Apollo?
[Apollo](https://www.apollographql.com/) é uma plataforma e uma série de ferramentas que disponibilizam a criação de APIs e clientes utilizando o padrão GraphQL.

#### O que é GraphQL?
[GraphQL](https://graphql.org/) é uma linguagem/especificação para consultas de API. Diferente do padrão REST comumente utilizado, é baseada em uma estrutura mais descritiva que resulta em dados previsíveis e exatos ao que um cliente necessita em uma requisição.

#### O que é Jest?
[Jest](https://jestjs.io/) é um framework JavaScript de testes. Muito extensível e largamente utilizado com aplicações JS.

#### O que é Testing Library?
[Testing Library](https://testing-library.com/) é um conjunto de utilitários para testar aplicações de diversos tipos. Ao longo do cursos, trabalharemos com sua [implementação voltada ao React](https://testing-library.com/docs/react-testing-library/intro), que nos permitirá testar e garantir a devida confiança nos componentes e na aplicação que estamos escrevendo.

#### O que é Storybook?
[Storybook](https://storybook.js.org/) é uma ferramenta que atua no lado do desenvolvimento dos componentes. Serve como uma camada de isolamento entre o componente desenvolvido e a aplicação final, além de já possuir uma estrutura rica em detalhes, o que faz com que seja um ótimo atalho para disponibilizar um catálogo dos componentes em sua aplicação.

#### O que é Cypress?
[Cypress](https://www.cypress.io/) é um framework de testes E2E (_end-to-end_ ou de ponta-a-ponta). Como o nome já diz, é responsável por testar a aplicação de forma completa, simulando pessoas interagindo com uma aplicação através de um navegador. Pode trabalhar de forma totalmente headless (via terminal e sem exibir o navegador) ou de forma "assistida", que permite acompanhar os visualmente testes durante sua execução.