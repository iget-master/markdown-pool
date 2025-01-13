<h1 align="center">
  <img src="./logo.svg" height="300" width="300" alt="Logo Markdown Pool" /><br>
  Markdown Pool
</h1>

![GitHub License](https://img.shields.io/github/license/iget-master/markdown-pool?labelColor=101010)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/iget-master/markdown-pool/commitlint.yml?style=flat&labelColor=101010)

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/All_Contributors-1-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

Tempos atrás tive vontade de criar uma enquete dentro do TabNews, mas não havia como fazer sem depender de comentarios, e pela politica do TabNews, comentarios curtos são desincentivados, impedindo que a enquete funcione como deveria. A solução? Criei um pequeno SaaS que permite você criar enquetes com até 5 escolhas, e embeddar direto no markdown.

Para criar uma enquete, basta visitar: https://md-poll.vercel.app/polls/create e preencher rapidamente o formulario com um título (a pergunta da sua enquete), e as opções que quer dar para o usuário votar, e salvar.

Será exibido uma prévia da enquete, e logo abaixo será exibido o código markdown para incluir a enquete em qualquer ambiente markdown.

## Stack

![JavaScript](https://img.shields.io/badge/javascript-323330.svg?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-38B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

![Vercel](https://img.shields.io/badge/vercel-000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-101010?style=for-the-badge&logo=supabase&logoColor=3ECF8E)

![Docker](https://img.shields.io/badge/docker-0db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

![GitHub](https://img.shields.io/badge/GitHub-fff?style=for-the-badge&logo=github&logoColor=181717)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088ff?style=for-the-badge&logo=github-actions&logoColor=fff)

## Arquitetura

Descrição sobre arquitetura escolhida, tanto de diretórios (monorepo, MVC, etc.) quanto de projeto (monolito, microsserviços, APIs, fluxo de comunicação, etc.), tudo conforme cabível dentro do escopo desejado.

Exemplos com fluxogramas, mermaid e/ou imagens são sempre bem-vindos.

## Rodando

Antes de iniciar com o desenvolvimento e os comandos, é importante definir as variáveis de ambiente no seu ambiente de desenvolvimento. Abaixo a listagem de quais definir para qual finalidade:

| Variável  | Tipo     | Necessidade            | Default | Descrição                  |
| :-------- | :------- | :--------------------- | :------ | :------------------------- |
| `EXAMPLE` | `string` | [Required \| Optional] | `Foo`   | Lorem ipsum dolor sit amet |

### Ação

`comando`

<!--
LISTA DE POSSÍVEIS AÇÕES

Linter
Checagem de Tipos
Conversão TS -> JS
Buscar/iniciar Migrações (Atualizações) de Banco de Dados
Atualizar Estrutura do Banco de Dados com Novas Migrações
Iniciar Testes Automatizados
Popular Banco de Dados para Execução Local
Iniciar o Servidor
 -->

## To-Do List

- [x] Impedir multiplos votos na mesma enquete por endereço IP
- [x] Salvar endereço de IP do criador da enquete
- [ ] Implementar rate-limit de criação de enquetes por IP
- [ ] Melhorar a interface de usuário e estilizar melhor as opções da enquete
- [ ] Implementar multi-idiomas
- [ ] Implementar estatisticas da enquete
- [ ] Implementar autenticação para evitar flood de enquetes (continuar permitindo sem autenticação, porém com rate-limit por IP)
- [ ] Implementar cache da renderização da opção
- [x] Pagina de estatisticas gerais (https://md-poll.vercel.app/polls)
- [ ] Implementar ✅ como feedback na opção votada

## Contrib

Definições curtas e objetivas de padrões a serem seguidos para contribuição de PRs.

Padrões em detalhes, explicações e informações/solicitações mais profundas em um "CONTRIBUTING.MD"; vide [https://github.com/jessesquires/.github/blob/main/CONTRIBUTING.md](https://github.com/jessesquires/.github/blob/main/CONTRIBUTING.md)

## Licença

This project is under [MTI License](https://choosealicense.com/licenses/mit/). A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://silvanomarques.vercel.app/"><img src="https://avatars.githubusercontent.com/u/59753526?v=4?s=100" width="100px;" alt="Silvano Marques"/><br /><sub><b>Silvano Marques</b></sub></a><br /><a href="#ideas-SilvanoGPM" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/iget-master/markdown-poll/commits?author=SilvanoGPM" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
