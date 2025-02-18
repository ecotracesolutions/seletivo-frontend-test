# Desafio EcoTrace Front-end

Nesse teste será avaliada a sua habilidade técnica como desenvolvedor front-end.

## Descrição da tarefa

Será necessário criar uma tela para listagem de usuários do sistema.

A listagem de usuários deve ser exibida em uma tabela, a qual possuirá uma coluna de ação para excluir definitivamente o usuário. Para evitar inconvinientes, ao clicar no botão de excluir o usuário deverá receber um diálogo de confirmação. Ao excluir o usuário com sucesso, o mesmo deve ser removido da tabela.

Sequência de colunas da tabela:

- Avatar
- Nome
- Idade
- Email
- Trabalho
- Ação

A tela deverá ter um título e uma breve descrição da tela.

Na parte superior da tela, deve conter um seletor de idiomas para alternar o idioma entre pt-BR e en-US. Ao alterar o idioma, os campos de: título, descrição e o cabeçalho da tabela devem refletir a alteração.

## Requisitos

[ ] Listar os usuários em uma tabela.

[ ] Os dados deverão ser carregados a partir de uma API que consumirá do JSON-SERVER, db.json.

[ ] A tabela deve conter paginação com 10 elementos por página, no máximo.

[ ] A tabela deve conter um botão de exclusão.

[ ] Ao tentar excluir um usuário, deve ser exibida uma mensagem de confirmação.

[ ] Ao excluir o usuário com sucesso, ele deverá desaparecer da tabela.

[ ] Deve existir um seletor que realize a internacionalização dos textos da tela.

[ ] A internacionalização deve ser entre os idiomas pt-BR e en-US.

[ ] Deve conter um seletor de idiomas que altere o idioma do site entre pt-BR e en-US

[ ] Deve ser criado um arquivo Dockerfile para executar o projeto.

## Diferencial

- Realização de testes unitários;
- Realização de testes E2E;
- Criação da documentação com Storybook;
- Boas práticas de desenvolvimento;

## Inicialização

```bash
# instale as dependências
pnpm i

# incialize o servidor faker em outro terminal
pnpm server:fake

# inicialize a aplicação
pnpm dev
```

## Documentação suporte

[NextJS](https://nextjs.org/)

[Tailwind](https://v3.tailwindcss.com/)

[Cypress](https://www.cypress.io/)

[Vitest](https://vitest.dev/) ou [Jest](https://jestjs.io/pt-BR/)

[StoryBook](https://storybook.js.org/)

[JSON Server](https://github.com/typicode/json-server)

## Entrega do teste

O projeto deve estar no GitHub e deve ser compartilhado com o [well-ecotrace](https://github.com/well-ecotrace) para avaliação.
