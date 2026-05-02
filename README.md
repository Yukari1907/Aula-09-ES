# Aula-09-ES

 Exercício Prático — Hands-on!
 
🎯 App: "Minha Lista de Tarefas" (To-Do List)

Contexto: Você vai modelar e prototipar um mini-app de lista de tarefas usando Arquitetura em Camadas + MVC.

# Parte 1 — Diagrama no Miro

O que fazer:
1. Abra o Miro e crie um novo board
2. Desenhe as 3 camadas do sistema (Apresentação, Negócio, Dados)
3. Dentro da camada de Apresentação, aplique o MVC:
  - Model: lista de tarefas (título, status: feito/pendente)
  - View: tela principal + tela de adicionar tarefa
  - Controller: ações de adicionar, marcar como feita, excluir
4. Use setas para mostrar o fluxo de uma ação (ex: usuário clica em "Adicionar Tarefa")
5. Adicione uma legenda de cores

# Parte 2 — Protótipo no Figma

O que fazer:
1. No Figma, crie um projeto chamado ToDoApp - SeuNome
2. Crie 2 telas (Frames mobile 390x844):
  - Tela 1: Lista de tarefas (com pelo menos 3 itens, botão de adicionar)
  - Tela 2: Modal ou tela de adicionar nova tarefa (campo de texto + botão salvar)
3. Conecte as telas com prototype links (botão "+" leva à Tela 2, botão salvar volta à Tela 1)
4. Nomeie os layers seguindo o MVC: View_ListaTarefas, View_AdicionarTarefa
