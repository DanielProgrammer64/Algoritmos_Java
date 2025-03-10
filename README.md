<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">

<h1> Desafios Java -> </h1>

Adicione os imports caso seja necessária formatação.

```java

// No começo do arquivo: 
import java.nio.file.*;
import java.nio.charset.StandardCharsets;
import java.io.IOException;

// Dentro do método principal:
String texto = "Olá, você está usando UTF-8 corretamente!";
        try {
            // Grava o texto no arquivo com UTF-8
            Files.write(Paths.get("seu_arquivo.txt"), texto.getBytes(StandardCharsets.UTF_8));
        } catch (IOException e) {
            e.printStackTrace();
        }

```


<h2> Desafio 1: </h2>
<p> Relativo ao atendimento de eventos, o hotel necessita de uma funcionalidade
que indique qual de seus dois auditórios é o mais adequado para um evento. O
auditório Alfa conta com 150 lugares e espaço para até 70 cadeiras adicionais. O
auditório Beta conta com 350 lugares, sem espaço para mais cadeiras. Desenvolva
um programa Java que receba o número de convidados do evento e faça uma
verificação sobre esse número: se for maior que 350 ou menor que zero, deverá ser
mostrada a mensagem “Número de convidados inválido”. Se o valor informado é
válido, deverá ser mostrado na tela qual dos auditórios é o mais adequado. No caso
do auditório Alfa, será preciso calcular ainda quantas cadeiras adicionais serão
necessárias, observando o limite citado anteriormente. </p>

Exemplo de execução:
![{6165865D-92BC-4C3E-8FA9-595235E586B7}](https://github.com/user-attachments/assets/803d4e5f-f697-425f-8a03-48f1a5bc018f)

<h2> Desafio 2: </h2> 
<p> Escreva um programa Java que faça a troca de quartos entre dois hospedes. É
preciso que ele receba o nome de um cliente e sua idade; o cliente a princípio será
hospedado no quarto A. Depois, o programa deve receber o nome de outro cliente
e sua idade; se o cliente for mais jovem, ficará no quarto B, mas, se a idade deste
for maior que a do primeiro cliente, ele ficará no quarto A e o primeiro cliente ficará
no quarto B. Além disso, se a pessoa mais velha for idosa (com 60 anos ou mais),
terá desconto de 40%. O programa deve mostrar ao final o nome do cliente que
ficou no quarto A e o desconto, se houver, e o nome do cliente que ficou no quarto. </p>

Exemplo de execução:
![{46AE8BD6-AC6C-4240-8D56-5E3A4E7EFFCE}](https://github.com/user-attachments/assets/d78f7128-09bb-4069-8c6e-16a63c755060)

<h2> Desafio 3: </h2>
<p> Escreva um programa Java que receba o valor padrão de uma diária e em
seguida receba vários nomes de hóspedes e suas idades. Caso a idade do
hóspede seja menor de 4 anos, ele não paga hospedagem – nesses casos, é
preciso que seja mostrada na tela a mensagem “(Nome do hóspede) possui
gratuidade”. Hóspedes com mais de 80 anos pagam metade – então dever ser
mostrado na tela “(Nome do hóspede) paga meia”. O usuário informará hóspedes
até digitar a palavra “PARE”, que interrompe a entrada de dados. Ao fim, o
programa deve mostrar a quantidade de gratuidades, a quantidade de meias
hospedagens e o valor total, considerando todos os hóspedes informados.</p>

Exemplo de execução: 

![{60A380CD-E6B8-4145-A13B-F3595EAD1C81}](https://github.com/user-attachments/assets/104da378-e3d1-44d5-a4be-18eae8879d82)

<h2> Desafio 4: </h2>

<p> Monte um algoritmo em que o usuário poderá cadastrar e pesquisar hóspedes. O
algoritmo deve oferecer um menu com três opções ao usuário: 1- cadastrar; 2-
pesquisar; 3- sair. A opção “cadastrar” deve permitir que o usuário informe um
nome de hóspede, gravando-o em memória (máximo de 15 cadastros; caso atinja
essa quantidade, mostre “Máximo de cadastros atingido”). A opção “pesquisar” deve
permitir que o usuário informe um nome e, caso seja encontrado um nome
exatamente igual, mostre a mensagem “Hóspede (nome) foi encontrado no índice
(índice onde foi cadastrado)”. Se o nome não foi encontrado, mostre “Hóspede não
encontrado”. O algoritmo deve permitir que o usuário realize essas operações
repetidas vezes, até que use a opção “3”, que encerra o algoritmo. </p>

Exemplo de execução:

![{02B1B180-FF9C-4845-8BC1-3BBBE8D0639F}](https://github.com/user-attachments/assets/6cb929fa-b466-430c-9b70-305a4c1b8792)

<h2> Desafio 5: </h2>

<p> Monte um programa Java que mostre na tela em formato de tabela os
quartos ocupados e os desocupados. Considere que o hotel tem 4 andares e 3
quartos por andar. Primeiro, o usuário registrará os quartos ocupados,
informando para cada ocupação o número do apartamento (andar de 1 a 4 e
número de quarto de 1 a 3). O programa deverá questionar “Deseja informar
outra ocupação? (S/N)” e o usuário poderá informar quantos quartos quiser, até
que responda “N” a essa pergunta. Em seguida, o programa mostrará uma
tabela, em que o primeiro andar é o inferior e o último, o superior, marcando
com X o quarto ocupado. </p>

Exemplo de execução:

![image](https://github.com/user-attachments/assets/30453f71-0ddc-44a0-b70e-eeb44422f91f)

![image](https://github.com/user-attachments/assets/d8828798-ef52-46fc-908e-273495a3e887)

</div>
