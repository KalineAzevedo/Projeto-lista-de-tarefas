# To-Do List Interativa
Este repositório contém a implementação de uma aplicação avançada de lista de tarefas (to-do list), no qual é possivel adicionar tarefas, marcar como feitas, pesquisa e até removê-las. Nessa aplicação interativa foi ultilizado HTML, CSS e JavaScript. Abaixo, detalho as principais funcionalidades e componentes do código para melhor compreensão:

## Funcionalidades da Aplicação:

### Adição de Tarefas:

- O formulário `todoForm` possibilita aos usuários adicionar novas tarefas à lista.
- A função `saveTodo` cria dinamicamente elementos HTML representando cada tarefa, com botões para marcar como concluída, editar e excluir.

### Edição de Tarefas:

- A função `updateTodo` permite a edição do título de uma tarefa existente.
- Ao clicar no botão de edição (`edit-todo`), o formulário de edição é exibido, preenchido com o título da tarefa selecionada.

### Marcação de Tarefas Concluídas:

- Cada tarefa possui um botão (`finish-todo`) para marcá-la como concluída, aplicando a classe CSS `done` para estilizar visualmente tarefas concluídas.

### Filtragem de Tarefas:

- O elemento `filterBtn` é um seletor que permite filtrar as tarefas exibidas com base no status ("all", "done", "todo").
- A função `filterTodos` ajusta a exibição das tarefas de acordo com a opção selecionada.

### Busca de Tarefas:

- O campo de busca (`searchInput`) possibilita que os usuários filtrem as tarefas com base em palavras-chave.
- A função `getSearchedTodos` exibe ou oculta tarefas com base na correspondência com o texto de busca.

### Armazenamento Local:

- Utilização da `localStorage` para armazenar e recuperar dados da lista de tarefas, garantindo que as tarefas persistam entre as sessões do navegador.
- Funções como `saveTodoLocalStorage`, `removeTodoLocalStorage`, `updateTodoStatusLocalStorage` e `updateTodoLocalStorage` gerenciam a interação com a `localStorage`.

## Imagens e ultilização:
Link para acesso:
https://lista-de-tarefas-todo-avancado.netlify.app/


Fotos:
![pginicial](https://github.com/KalineAzevedo/Projeto-lista-de-tarefas/assets/137228416/b95afc05-4771-49e3-b775-c25fcefcac36)
![remover](https://github.com/KalineAzevedo/Projeto-lista-de-tarefas/assets/137228416/f6e886c3-b4ef-4494-a5ee-5fbb4e9fb3cc)
![pesquisar](https://github.com/KalineAzevedo/Projeto-lista-de-tarefas/assets/137228416/ec735d55-ce9d-40a3-9bea-fcebc3e8ee33)








