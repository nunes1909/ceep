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
5. **Implementação do LayoutManager.**
    - Pode ser implementado na classe main de forma dinâmica.
    - Pode ser implementado diretamente no xml de forma estática.
6. **Iniciando uma Activity esperando um resultado.**
    - O método "startActivityForResult" serve para iniciar uma activity esperando um resultado. (requestCode).
    - O método "setResult" serve para retorar uma activity informando um resultado. (resultCode).
7. **Implementação do método onActivityResult.**
    - Este método serve para verificar se o requestCode e resultCode foram informados.
8. **Implementação de uma Interface de constantes.**
9. **Refatoração de todo o código Java e Layout.**
10. **Finalizando o projeto.** 🚀🎉

![2022-03-13 21-52-34](https://user-images.githubusercontent.com/80295127/158087841-80d667bf-7485-4dd4-9c2f-d5cce462c465.gif)
