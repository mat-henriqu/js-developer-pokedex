
# Pokedex

Este projeto é uma Pokédex web simples, que exibe uma lista dinâmica de Pokémon utilizando a PokeAPI. Ele permite a navegação e visualização de vários Pokémon, com a funcionalidade de carregar mais resultados à medida que o usuário interage com o botão "Load More". A aplicação é responsiva e utiliza tecnologias como HTML, CSS, e JavaScript.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação da página e conteúdo semântico.
- **CSS3**: Estilos e design da interface. Utiliza fontes do Google e Normalize.css para garantir consistência entre navegadores.
- **JavaScript (ES6+)**: Lógica do projeto, integração com a PokeAPI e manipulação do DOM.
- **PokeAPI**: API utilizada para obter os dados dos Pokémon.
- **Normalize.css**: Biblioteca para garantir que todos os navegadores renderizem elementos de forma mais consistente.
- **Google Fonts**: Fonte personalizada Roboto para uma melhor estética visual.

## 📂 Estrutura do Projeto

```bash
.
├── assets
│   ├── css
│   │   ├── global.css   # Estilos globais
│   │   └── pokedex.css  # Estilos específicos para a Pokedex
│   ├── js
│   │   ├── main.js      # Lógica principal da aplicação
│   │   ├── poke-api.js  # Funções para consumir a PokeAPI
│   │   └── pokemon-model.js  # Definição do modelo de dados do Pokémon
├── index.html            # Página principal
```

## 📦 Funcionalidades

- **Exibição de Pokémon**: A lista inicial de Pokémon é exibida ao carregar a página.
- **Paginação**: A função "Load More" permite carregar mais Pokémon ao clicar no botão.
- **Consumo da PokeAPI**: A aplicação se integra com a PokeAPI para buscar os dados dos Pokémon de forma dinâmica.

## 🚀 Como Executar o Projeto

1. Clone o repositório em sua máquina local:
   ```bash
   git clone https://github.com/mat-henriqu/js-developer-pokedex.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd js-developer-pokedex
   ```
3. Abra o arquivo `index.html` no navegador ou use uma extensão como **Live Server** no VS Code para ver o projeto em execução.

## 🌐 API Utilizada

- [PokeAPI](https://pokeapi.co/): API pública usada para obter dados dos Pokémon.

## 📸 Demonstração

Adicione uma captura de tela ou gif da aplicação em funcionamento para ilustrar como a Pokedex funciona.

## ✨ Melhorias Futuras

- Adicionar funcionalidade de busca para filtrar Pokémon por nome.
- Implementar a exibição de detalhes ao clicar em um Pokémon.
- Melhorar a responsividade da aplicação para diferentes dispositivos.
