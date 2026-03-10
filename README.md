Implementação do Carrinho

Foi implementado um sistema de carrinho de compras utilizando React Context API e useReducer para gerenciamento de estado global. O estado do carrinho permite adicionar, remover, atualizar quantidade de produtos e limpar o carrinho.

Também foi criado um hook personalizado (useCart) para facilitar o acesso ao contexto em qualquer componente da aplicação. O carrinho foi integrado à página de detalhes do produto, permitindo adicionar itens através do botão de compra.

Além disso, foi implementada a persistência dos dados com localStorage, garantindo que os itens do carrinho permaneçam mesmo após recarregar a página.

Foi criada a página /cart, onde é possível visualizar os produtos adicionados, alterar quantidades, remover itens e ver o valor total da compra. A Navbar também foi integrada ao carrinho, exibindo a quantidade total de itens e permitindo acesso rápido à página do carrinho.
