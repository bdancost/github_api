
# GitHub API - Buscando Usuários com Fetch

Este projeto é uma aplicação web que permite buscar informações de usuários do GitHub utilizando a API oficial. A interface simples e intuitiva permite ao usuário digitar o nome de um perfil no GitHub e visualizar os detalhes do usuário, como foto de perfil, nome, biografia e lista de repositórios.

## Índice

- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Instalação e Uso](#instalação-e-uso)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Contribuição](#contribuição)

## Visão Geral

A aplicação permite realizar buscas de usuários na plataforma GitHub, utilizando a [GitHub API](https://docs.github.com/en/rest). É possível visualizar informações básicas do perfil, como:
- Foto do perfil
- Nome do usuário
- Biografia
- Lista dos últimos 10 repositórios públicos

## Funcionalidades

- **Busca de usuários**: Busca por usuários no GitHub através do nome de usuário.
- **Exibição de informações**: Exibe a foto do perfil, nome, biografia e uma lista dos repositórios públicos.
- **Mensagens de erro**: Mostra uma mensagem amigável quando o usuário não é encontrado.

## 🚀🚀 Tecnologias Utilizadas

- <img src="https://cdn-icons-png.flaticon.com/512/732/732212.png" width="20" height="20" alt="HTML5 Icon"> **HTML5**: Estrutura básica da aplicação.
- <img src="https://cdn-icons-png.flaticon.com/512/732/732190.png" width="20" height="20" alt="CSS3 Icon"> **CSS3**: Estilização e layout responsivo.
- <img src="https://cdn-icons-png.flaticon.com/512/919/919828.png" width="20" height="20" alt="JavaScript Icon"> **JavaScript (ES6+)**: Manipulação do DOM, chamadas à API e lógica de renderização.
- <img src="https://cdn-icons-png.flaticon.com/512/2913/2913970.png" width="20" height="20" alt="API Icon"> **API do GitHub**: Integração para obtenção de dados dos usuários.



## Instalação e Uso

1. **Clone o repositório**:
   ```bash
   https://github.com/bdancost/github_api.git
   ```
2. **Abra o arquivo `index.html` em seu navegador** para visualizar a aplicação.

Não é necessário nenhum ambiente de desenvolvimento específico ou dependências externas para rodar o projeto, basta um navegador moderno que suporte ES6.

## Estrutura do Projeto

```
|-- src
|   |-- css
|   |   |-- reset.css
|   |   |-- styles.css
|   |-- scripts
|   |   |-- index.js
|   |   |-- objects
|   |   |   |-- screen.js
|   |   |   |-- user.js
|   |   |-- services
|   |   |   |-- user.js
|   |   |   |-- repositories.js
|   |   |-- variables.js
|-- index.html
```

### Descrição dos Arquivos

- **`index.html`**: Estrutura da página e layout.
- **`styles.css`**: Estilos gerais da aplicação.
- **`reset.css`**: Estilo de reset para garantir a consistência entre navegadores.
- **`index.js`**: Arquivo principal de controle das interações do usuário.
- **`user.js`**: Lida com a estrutura de dados do usuário.
- **`repositories.js`**: Gerencia a busca e exibição de repositórios do usuário.
- **`screen.js`**: Responsável pela renderização das informações na tela.
- **`variables.js`**: Contém variáveis globais como a URL base da API.

## Contribuição

Contribuições são sempre bem-vindas! Se você tiver sugestões de melhorias, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

1. *Fork* o projeto.
2. Crie uma nova *branch*:
   ```bash
   git checkout -b feature/minha-nova-feature
   ```
3. Faça suas alterações e *commit*:
   ```bash
   git commit -m 'Adiciona nova funcionalidade'
   ```
4. *Push* para a *branch*:
   ```bash
   git push origin feature/minha-nova-feature
   ```
5. Abra um *pull request*.



