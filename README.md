# bc-test-react
Teste para desenvolvedores REACT - BCompany


## Teste Técnico: Desenvolvedor React (Nível Pleno) - Gerenciamento de Clientes com Vite
Objetivo:

Criar uma aplicação simples em React com Vite que gerencia um conjunto de clientes. O candidato deverá demonstrar o uso de hooks, manipulação de eventos, gerenciamento de estado e a criação de uma interface de usuário para visualizar, adicionar, editar e excluir clientes.

### Requisitos Funcionais

* Adicionar Cliente: O usuário deve ser capaz de adicionar um novo cliente com os seguintes dados: Nome, Email e Telefone.

* Excluir Cliente: O usuário deve ser capaz de excluir um cliente da lista.

* Editar Cliente:  O usuário deve ser capaz de editar as informações de um cliente (Nome, Email, Telefone).

* Filtrar Clientes: O usuário deve ser capaz de filtrar a lista de clientes, por exemplo, por nome, ou por um texto que contenha parte do nome ou email.

* Validação de Entrada: Ao adicionar ou editar um cliente, a entrada deve ser validada para garantir que o nome e email não sejam vazios, e que o email tenha um formato válido.

### Recomendações Técnicas

* Vite para Configuração do Projeto:  Iniciar um projeto React utilizando Vite. O projeto deve ser configurado com as dependências básicas necessárias para o desenvolvimento.

* React e Hooks: Utilizar componentes funcionais e hooks do React (useState, useEffect).

* Gerenciamento de Estado: O estado da lista de clientes deve ser gerenciado corretamente (por exemplo, usar o useState ou um gerenciador de estado como useReducer para maior complexidade).

* Componentização: A aplicação deve ser bem componentizada. Os componentes devem ser reutilizáveis e responsáveis por uma única tarefa (ex: um componente para a entrada de novo cliente, um para a listagem de clientes, etc.).

* Uso de Formulários: O formulário de adição/edição de clientes deve ser bem implementado, com controle de estado para cada campo (Nome, Email, Telefone).

* Manipulação de Eventos: Ao clicar nos botões (adicionar, excluir, editar, etc.), os eventos devem ser tratados corretamente.

* Estilização: A aplicação pode ser estilizada com CSS ou uma biblioteca de UI como o Material-UI ou Styled Components.

* Boas Práticas: Código limpo, organizado e com comentários explicativos onde necessário. 

* Utilizar destruturação de objetos e arrays de maneira eficiente.



Instruções de Configuração:

Inicializar o Projeto com Vite:

Primeiramente, o candidato deve criar um projeto React com Vite:

npm create vite@latest cliente-management --template react
cd cliente-management

npm install
Isso vai criar a estrutura básica do projeto com React.

Instalar Dependências: Caso o candidato deseje, pode instalar algumas dependências adicionais como react-router-dom, styled-components ou @mui/material, mas não é obrigatório.

npm install react-router-dom styled-components @mui/material

Rodando o Projeto: O projeto pode ser rodado com o comando:

npm run dev
Isso irá iniciar o servidor local para que o candidato consiga ver a aplicação em tempo real enquanto desenvolve.

### Exemplo de Funcionalidade Esperada:

* Quando o usuário adiciona um cliente, ele aparece na lista com os dados (Nome, Email, Telefone).
* O usuário pode editar as informações de um cliente, alterando o nome, o email ou o telefone.
* O usuário pode excluir um cliente da lista.
* O usuário pode filtrar a lista de clientes com base no nome ou email.
* Desafio Adicional (Opcional):
* Persistência de Dados:
* Implemente a persistência dos dados utilizando localStorage para garantir que os clientes não sejam perdidos quando a página for recarregada.

### Instruções

Faça um fork no projeto, após finalizar crie um pull request.

Caso queira, você pode usar a biblioteca que achar mais apropriada para realizar a tarefa (ex: Material UI, Styled Components, etc.).
Envie o link do repositório GitHub com as instruções para rodar o projeto e qualquer outra consideração que julgar importante.
Esse teste foi adaptado para gerenciar clientes em vez de tarefas, mas os requisitos e a estrutura permanecem semelhantes. A ideia é que o candidato use as mesmas habilidades técnicas, como o uso de hooks, gerenciamento de estado, validação de formulários e organização de componentes, para criar uma aplicação funcional de cadastro e gerenciamento de clientes. O uso do Vite para iniciar o projeto proporciona um ambiente de desenvolvimento moderno e rápido.


