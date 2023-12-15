# Pokémon Deck Builder

Este projeto é uma aplicação Angular 15 que permite aos usuários criar decks Pokémon, consultando uma API de Pokémon para listar cartas e realizar operações básicas.

## Funcionalidades

- **Listagem de Decks:** A página principal exibe uma lista de decks existentes, cada um identificado por um nome. Os usuários podem clicar em um deck para ver mais detalhes.

- **Criação de Decks:** Os usuários podem criar novos decks, fornecendo um nome e selecionando entre 24 e 60 cartas da lista de cartas disponíveis.

- **Detalhes do Deck:** Ao clicar em um deck, os usuários podem ver detalhes específicos do deck, incluindo as cartas incluídas.

- **Pesquisa de Cartas:** Os usuários podem pesquisar cartas pelo nome, facilitando a localização de cartas específicas na lista.

- **Visualização de Detalhes da Carta:** Uma modal permite aos usuários visualizar detalhes específicos de uma carta selecionada.

## Arquitetura

O projeto segue uma arquitetura Angular 15 e faz uso de vários componentes, serviços e modelos para organizar e modularizar o código. Alguns dos principais componentes incluem:

- **pokemon-list:** Responsável por exibir a lista de cartas, permitir a seleção de cartas para um novo deck e interagir com os serviços.

- **deck-details:** Exibe detalhes específicos de um deck, incluindo as cartas que o compõem.

- **card-details-modal:** Uma modal para visualizar detalhes específicos de uma carta.

- **add-card-dialog:** Um componente para adicionar uma nova carta ao deck.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).
