# Arrays

Um **array** significa que irá armazenar todos os seus dados contiguamente (um ao lado do outro) na memória.

Agora, suponha que você queira adicionar mais um dado. No entanto a próxima "gaveta" na memória está ocupada.
Você irá precisar solicitar ao computador uma área de memória em que coubessem todos os seus dados. Então você as moveria para lá.
Arrays são ótimos se você deseja ler elementos aleatórios, pois pode encontrar qualquer elemento instantaneamente em um array.

### Exemplo:
É como se você estivesse indo ao cinema com os seus amigos e encontrassem um lugar para sentar, mas outro amigo se juntasse a vocês e não houvesse lugar para ele. Vocês todos precisariam se mover para encontrar um lugar onde todos coubessem.
Se outro amigo aparecesse, vocês ficariam sem lugar novamente - e todos precisariam se mover uma segunda vez!

Da mesma forma, **adicionar novos itens a um array será muito lento.**
Uma forma fácil de resolver isso é "reservar lugares". Isso é uma forma de contornar o problema, mas precisa ficar atendo às desvantagens.

### Desvantagens:

 - Você pode não precisar dos espaços extras que reservou: então a memória será desperdiçada. Você não está utilizando a memória, mas ninguém mais pode usá-la também.
 - Você pode precisar adicionar mais dados ao seu array, então você terá de mover seus itens de qualquer maneira.

# Listas Encadeadas
Nas listas encadeadas seus dados podem estar em qualquer lugar da memória.
Cada item armazena o endereço do próximo item da lista. Um monte de endereços aleatórios de memória estão ligados. Você o coloca em qualquer lugar da memória e armazena o endereço do dado anterior.
Nunca precisará mover os seus dados. Se existir espaço na memória, você terá espaço para a sua lista encadeada.

Listas encadeadas são ótimas se você quiser ler todos os itens, um de cada vez: pode ler um item, seguir para o endereço do próximo item e fazer isso até o fim da lista. Mas se você quiser pular de um item para outro, as listas encadeadas são terríveis.

## Inserindo algo no meio da lista

Usando listas encadeadas:

 - Basta mudar o endereço para o qual o elemento anterior aponta.

Usando arrays:

 - Você deve mover todos os itens que estão abaixo do endereço de inserção.

Se houver espaço, pode ser necessário mover tudo para um novo local. Listas encadeadas são melhores caso você queira inserir um elemento no meio de uma lista.

## Deleções

É mais fácil fazer isso usando **listas encadeadas**, pois é necessário mudar apenas o endereço para o qual o elemento anterior está apontando.
Com **arrays**, tudo precisa ser movido quando um elemento é eliminado.


## Resumo

 - A memória do seu computador é como um conjunto gigante de gavetas.
 - Quando se quer armazenar múltiplos elementos, usa-se um array ou uma lista.
 - no Array, todos os elementos são armazenados um ao lado do outro.
 - Na Lista, os elementos estão espalhados e um elemento armazena o endereço do próximo elemento.
 - Arrays permitem leituras rápidas.
 - Listas encadeadas permitem rápidas inserções e eliminações.
 - Todos os elementos de um array devem ser do mesmo tipo(todos ints, todos doubles, e assim por diante).




###### Foi usado o livro: Entendendo algoritmos - Um guia ilustrado para programadores e outros curiosos - Aditya Y. Bhargava
