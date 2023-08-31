# DATA CHALLENGE 2

---

Bem vindos ao segundo DATA CHALLENGE!

Aqui traremos alguns problemas que envolvam python, dados, aprendizado de máquina e afins. O intuito é que vocês tentem ao máximo praticar com esses desafios que trarão por ventura, alguns tópicos interessantes.

#CHALLENGE: Funções e Listas

Peter é um jovem rapaz de 10 anos que adora comer doces. Ele costuma guardar esses doces variados em uma mochila.

Podemos representar a mochila de Peter como uma lista da seguinte forma:

`doces = [1,1,2,3,4,5,5,5] `

Nesse caso, a mochila de Peter contém 8 doces, sendo 2 do tipo `1`, 1 do tipo `2`, 1 do tipo `3`, 1 do tipo `4` e 3 do tipo `5`.

Segundo médico de Peter, ele deve reduzir seu consumo de doces pela metade. E como Peter é esperto, ele quer consumir a maior variedade de doces possível seguindo a orientação do Médico.

Ex:

- Se a mochila dele tiver 8 doces da seguinte forma : `doces = [1,1,2,3,4,5,5,5] ` - Peter consumirá no máximo 4 variedades.

- Se a mochila dele tiver 4 doces da seguinte forma : `doces = [1,1,2,3]` - Peter consumirá no máximo 2 variedades.

- Se a mochila dele tiver 8 doces da seguinte forma : `doces = [1,1,2,3,2,1,3,2]` - Peter consumirá no máximo 3 variedades.

...

Obs: Vamos supor que sempre haja uma quantidade `par` de doces na mochila.




## Tarefa

Construa uma lógica para a função `DocesPeter()` onde ela receba como parâmetro uma `lista` contendo os doces e seus tipos, e devolva o valor da quantidade máxima de doces que Peter pode consumir (a função deve devolver um `int`).

Não se assuste caso você não esteja acostumado a ver a função assim:

```python

def DocesPeter(lista_tipos_doces) -> int:

```

Isso só significa que a função vai receber como parâmetro essa `lista_tipos_doces` e devolverá um número do tipo `int`.

Aqui a ideia é deixar a criatividade fluir.

É um tipo de problema que não tem 1 tipo de solução, mas lembre que no primeiro CHALLENGE havia uma solução que torna mais legível e simples o código.

Não ligue para o tempo que vai levar, apenas se concentre em achar uma solução e verificar suas heurísticas(lógica).

Esse é um problema que não precisa de nenhuma biblioteca pronta! Basta colocar a criatividade pra jogo.



