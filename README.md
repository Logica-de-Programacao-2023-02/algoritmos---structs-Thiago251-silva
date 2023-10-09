# Algoritmos Structs

1. Crie uma struct chamada Circulo com o campo "raio". Escreva uma função que receba um Circulo como parâmetro e calcule
   a área do círculo (área = pi * raio * raio). Dica: use a constante math.Pi para representar o número pi.
2. Crie uma struct chamada Pessoa com os campos "nome", "idade" e "endereço". O campo "endereço" deve ser uma outra
   struct com os campos "rua", "número", "cidade" e "estado". Escreva uma função que receba uma Pessoa como parâmetro e
   imprima seu endereço completo.
3. Crie uma struct chamada Triângulo com os campos "base" e "altura". Escreva uma função que receba um Triângulo como
   parâmetro e calcule a área do triângulo (área = base * altura / 2).
4. Crie uma struct chamada Playlist com os campos "nome" e "músicas". O campo "músicas" deve ser um slice de structs,
   cada uma representando uma música com os campos "título", "artista" e "duração". Escreva uma função que receba uma
   Playlist como parâmetro e imprima o nome da playlist, o tempo total da playlist e as informações de cada música.
5. Usando as mesmas structs do exercício anterior, escreva uma função que receba um título de música
   como parâmetro e retorne uma lista das Playlists que possuem esse título.
6. Crie uma struct chamada Funcionário com os campos "nome", "salário" e "idade". Escreva funções que permitam aumentar
   ou diminuir o salário do funcionário em uma determinada porcentagem e uma função que calcule o tempo de serviço do
   funcionário (considerando que ele começou a trabalhar aos 18 anos).
7. Crie uma struct chamada Animal com os campos "nome", "espécie", "idade" e "som". Escreva funções que permitam
   modificar o som que o animal faz e uma função que imprima as informações do animal e o som que ele faz.
8. Crie uma struct chamada Viagem com os campos "origem", "destino", "data" e "preço". Escreva uma função que receba um
   slice de Viagens como parâmetro e retorne a viagem mais cara.
9. Crie uma struct chamada Aluno com os campos "nome", "idade" e "notas". O campo "notas" deve ser um slice de float64,
   representando as notas que o aluno tirou em uma determinada disciplina. Escreva funções que permitam adicionar ou
   remover notas do aluno, calcular a média das notas e imprimir o nome, idade e média do aluno.
10. Crie uma struct chamada Filme com os campos "título", "diretor", "ano" e "avaliações". O campo "avaliações" deve ser
    um slice de inteiros representando as notas que o filme recebeu dos espectadores. Escreva funções que permitam
    adicionar ou remover avaliações do filme, calcular a média das avaliações e imprimir as informações do filme e sua
    média de avaliações.

