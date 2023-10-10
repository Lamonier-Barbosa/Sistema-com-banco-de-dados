# RESTful API 

## Sobre o Projeto💡

Esta API RESTful foi desenvolvida utilizando JavaScript, Node.js, pacotes npm e banco de dados PostgreSQL. O projeto foi realizado em dupla, com o uso do Git e GitHub para mesclar os códigos e subi-los na branch principal. Esta API conta com um sistema de segurança com os dados do usuário sendo **Criptografados**.

## Ferramentas Utilizadas 👨🏻‍💻
<p>
<img  src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"
<p/>
<img  src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"
<p/>
<img  src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"
<p/>
<img  src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge"
<p/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"
p/>

- **Linguagem de Programação**: JavaScript
- **Ambiente de Execução**: Node.js
- **Pacotes NPM**: Express, PG, Nodemon, Bcrypt, Jasonwebtoken e Dotenv.
- **Banco de Dados**: PostgreSQL
- **IDE**: Visual Studio Code
- **Teste de API**: Postman
- **Controle de Versão**: Git e GitHub

## Funcionalidades 🚀

1. **Cadastrar Usuário**: Permite a criação de um novo usuário.
2. **Fazer Login**: Autentica um usuário existente.
3. **Detalhar Perfil do Usuário Logado**: Exibe detalhes do perfil do usuário autenticado.
4. **Editar Perfil do Usuário Logado**: Permite a edição do perfil do usuário autenticado.
5. **Listar Categorias**: Exibe uma lista de todas as categorias disponíveis.
6. **Listar Transações**: Exibe uma lista de todas as transações do usuário autenticado.
7. **Detalhar Transação**: Exibe detalhes de uma transação específica.
8. **Cadastrar Transação**: Permite a criação de uma nova transação.
9. **Editar Transação**: Permite a edição de uma transação existente.
10. **Remover Transação**: Permite a remoção de uma transação existente.
11. **Obter Extrato de Transações**: Exibe um extrato das transações do usuário autenticado.
12. **Filtrar Transações por Categoria** Permite ao usuário filtrar suas transações por categoria.

## Como Utilizar ⤵️

Para utilizar esta API, siga os passos abaixo:

1. Clone o repositório para sua máquina local usando `git clone`.
2. Navegue até o diretório do projeto e execute `npm install -y` para instalar todas as dependências necessárias.
3. Após instalar o npm, basta instalar suas dependências com o seguintes comando `npm i express pg`, `npm i -D nodemon`, `npm i bcrypt`, `npm i jsonwebtoken`, `npm i dotenv --save`.
4. Após instalar todas as suas dependências, vá para o **Beekeeper** ou qualquer editor e gerenciador SQL de banco de dados. Cole os comando que estão no arquivo **dump.sql**, depois disso, no seu Vscode, crie um arquivo fora da pasta app, chamado de **.env** e faça a conexão com o seu banco de dados.
5. Inicie o servidor usando `npm run dev` (ou comando similar dependendo da sua configuração).
6. Use o Postman (ou qualquer cliente HTTP de sua escolha) para enviar solicitações para a API.

## Como Contribuir ⚙️

Este projeto é aberto para contribuições. Sinta-se à vontade para fazer um fork e enviar suas alterações através de um Pull Request.

## Licença 
<img src="https://badgen.net/github/license/micromatch/micromatch">

Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
