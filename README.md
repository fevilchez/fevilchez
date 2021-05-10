# Algoritmo de Horn

Esse programa recebe um input de uma formula FNC e realiza a verifica se ela é de horn, caso não for, retornará NA, se a verificação retornar positiva, o programa verifica se a formula é sat ou unsat.

## Algoritmo utilizado

Para a realização desse projeto utilizamos a linguagem de programação C e utilizamos o Visual Studio Code como nosso editor, primeiramente recorremos ao uso de um while para a leitura total da formula inserida, realizamos a contagem de todos os parentes e verificamos se esse numero é maior que 200, se for significa que existem mais do que 100 clausulas e o programa encerra, para verificar se a formula é de horn realizamos a leitura de uma clausula de cada vez e contamos seus literais positivos, caso houver mais do que um significa que a formula não é de horn e retorna o ouput "NA",também examinamos casos de que o "&" se encontra dentro das clausulas causando um erro e retornando que a formula não é de horn, caso a formula for de horn, programa realiza a verificação de se a formula é contraditória ou possível, para isso realizamos a leitura da formula e adicionamos todos os literais negados e literais afirmados em duas listas separadas, e se todos os literais negados da clausula estiverem dentro do fecho de horn, a formula é contraditória, caso o contrario o programa retornara que a formula é possível.

#### Autores

Israel Torres (40715)(PL3) e Felipe Vilchez (40752)(PL2)
