# PokemonInicialDIO
Desafio DIO.me: Pokemon Inicial

## Descrição
No mundo dos jogos Pokémon, os treinadores começam sua jornada escolhendo um dos três Pokémons iniciais: Bulbasaur, Charmander e Mewtwo. Cada treinador escolhe um dos quatro pokemons. Seu desafio é criar uma solução que permita ao jogador escolher um dos Pokémons iniciais e exibir uma mensagem de boas-vindas e o Pokémon escolhido.

## Entrada
Você receberá um número inteiro que representa a escolha do treinador: 1 para Bulbasaur, 2 para Charmander, 4 Pikachu e 5 para Mewtwo.

## Saída
A saída deve ser uma mensagem de boas-vindas que inclua o nome do Pokémon escolhido.

## Explicação do código:

Entrada de dados: gets("1", "2", "4", "5") é uma função hipotética usada para obter a escolha do treinador. O parseInt() é então utilizado para converter a escolha de string para um número inteiro, o que é necessário para comparações numéricas a seguir.

### Variáveis:

escolhaDoTreinador: Armazena o número inteiro que representa a escolha do treinador.
pokemonEscolhido: Variável que será utilizada para armazenar o nome do Pokémon escolhido com base na escolha do treinador.

### Condições de escolha do Pokémon:

Aqui, o código utiliza uma série de declarações if-else if-else para determinar qual Pokémon corresponde à escolha do treinador (escolhaDoTreinador).

Se escolhaDoTreinador for igual a 1, 2, ou 4, então pokemonEscolhido receberá o nome correspondente ao Pokémon ("Bulbasaur", "Charmander", "Pikachu", respectivamente).

Se nenhuma das condições acima for verdadeira, o Pokémon escolhido será "Mewtwo".

### Impressão do resultado:

Finalmente, o código imprime uma mensagem informando qual Pokémon foi escolhido pelo treinador, utilizando a variável pokemonEscolhido para inserir o nome do Pokémon na mensagem.

## Resultado

![PrintDesafio3](https://github.com/user-attachments/assets/f708f5b4-9293-4e09-add2-1846456c01c2)
