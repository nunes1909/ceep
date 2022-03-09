## Dados do repositório:
Nome do App: Ceep - Anotações.<br>
Curso: Recycler View parte 1: Listas flexíveis e performáticas.<br>
Recursos: RecyclerView + ConstraintLayout

## Este aplicativo aborda:
1. **Diferença entre a ListView e RecyclerView.**
    - A ListView ao gerar novas Views, mantém todas as views anteriores armazenadas na memória.
    - Ja a RecyclerView ao invés de manter todas as views armazenadas na memória, ela faz o processo de "reciclagem" das views.
2. **Criação da RecyclerView no projeto.**
3. **Criação do Adapter da RecyclerView.**
    - Implementação do construtor do Adapter.
    - Implementação da classe ViewHolder com o seu construtor. 
    - Entendendo cada processo do Adapter e seus métodos.
      - onCreateViewHolder -> ``` Método responsável por "inflar", ou, setar o layout dos itens da RecyclerView. ```
      - onBindViewHolder -> ``` Método responsável por a partir das posições, inserir os dados do objeto na RecyclerView. ```
      - getItemCount -> ``` Método responsável por definir o tamanho a RecyclerView. ```
4. **Implementação do Adapter na classe main.**
5. **Implementação da classe LinearLayoutManager.**
    - Classe responsável por gerenciar o layout utilizado na RecyclerView.  
