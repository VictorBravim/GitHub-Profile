# GitHub Profile Viewer

![Dia6](https://github.com/VictorBravim/GitHub-Profile/assets/122113588/04244c51-1fa8-4310-b15a-ad6c4d63b15f)

Este projeto consiste em uma página web simples que permite aos usuários pesquisarem perfis do GitHub e exibe informações sobre o usuário, incluindo detalhes do perfil e seus repositórios.

## <code>Estrutura do Projeto</code>

- index.html: Arquivo principal HTML contendo a estrutura da página.
- style.css: Arquivo de estilo CSS que define o layout e a aparência da página.
- script.js: Arquivo JavaScript responsável por interagir com a API do GitHub e manipular o DOM.

## <code>Organização do Código</code>

- HTML: O código HTML está estruturado com formulário de pesquisa, área principal para exibir informações do usuário e repositórios.
- CSS: Os estilos estão definidos usando a fonte Poppins, com esquema de cores escuro. Há uma adaptação responsiva para telas menores (max-width: 500px).
- JavaScript: O código JavaScript utiliza a biblioteca Axios para fazer chamadas assíncronas à API do GitHub. Ele manipula a resposta da API para exibir as informações do usuário e seus repositórios.

## <code>Funcionalidades</code>
1. Pesquisa de Usuário:
  - O formulário permite que os usuários insiram o nome de usuário do GitHub para buscar informações.

2. Exibição de Informações:
  - As informações do usuário, como nome, biografia, seguidores, seguindo e repositórios, são exibidas em um card estilizado.

3. Repositórios do Usuário:
  - Os cinco primeiros repositórios do usuário são exibidos com links para seus respectivos perfis no GitHub.
  
4. Tratamento de Erros:
  - Em caso de usuário não encontrado, um card de erro é exibido com uma mensagem apropriada.

## <code>Como Usar</code>
1. Clone o repositório para sua máquina local.
2. Abra o arquivo index.html em um navegador web.
3. Insira o nome de usuário do GitHub no campo de pesquisa e pressione "Search".
4. As informações do usuário serão exibidas na área principal da página.

## <code>Melhorias Futuras</code>
- Autenticação: Adicione autenticação para aumentar o limite de requisições à API do GitHub.
- Mais Detalhes: Expanda as informações exibidas, como detalhes de commits, issues, etc.
- Ordenação de Repositórios: Permita que o usuário escolha a ordem de exibição dos repositórios.

## <code>Contribuição</code>
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, propor melhorias ou enviar pull requests.

## <code>Licença</code>
Este projeto está sob a Licença MIT.
