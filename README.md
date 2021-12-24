# Ciência da Computação / Cietista da Computação:

Bits;
Binários;
ASCII;
Elementos de Programação;
Algoritmos;
Scratch;
Expressões Booleanas.

Importante ter conhecimento de uso de Sistemas Operacional por linhas de comandos (Linux ou Windows).

Aprender a fazer algoritmos que resolva problemas e otimizar processos.

# Bits;

1000 100 
10 1

Exemplo:

número: 127

Centena    Dezena    dezena
100      | 10       | 1   -->  Sistema Binario
1 *        2 *        7   <--  Decimal (Potencia de 10 '0-9' com 10 possibilidades)

Exemplo decimal: 
10 ** 0
10 ** 1
10 ** 2

Numeros Binario ** 2 (0-1):

2 ** 0 = 1
2 ** 1 = 2
2 ** 2 = 4
2 ** 3 = 8

Exemplo do Binario (0-1, com 2 possibilidades) conversão:

numero=7

8   4   2   1 (bytes conjunto de 8 bits)
0   1   1   1 binario

numero=5
8   4   2   1
0   1   0   1  binanrio

numero=3
8   4   2   1
0   0   1   1 binario

numero=6
8   4   2   1
0   1   1   0 binario

numero=2
8   4   2   1
0   0   1   0 binarios

# Tabela ASCII;

2 ** 8 = 8 bits = 1 byte

1 * 2 = 2
2 * 2 = 4
4 * 2 = 8
8 * 2 = 16
16 * 2 = 32
32 * 2 = 64
64 * 2 = 128
128 * 2 = 256

# HDs

Quando seu arquivo é deletado no hd, ele é gravado no hd como 0(zeros). (Esquecido dentro do HD).

Porem ainda assim é possivel resgatar os dados com ferramentas forense.

# Algoritmo

Um loop infinito é ruim. Como cientista da programação voce precisa antecipar os problemas.

É uma sequencia de intruções para resolver um problema.

Exemplo:

#include <stdio.h>

int
main(void)
{
        printf("Hello Word!\n");
}


Apos salvar esse conteudo em um arquivo exemplos 'hellow.c' podemos fazer a copilação com o seguinte comando:

*gcc hellow.c*

Se não apresentar nenhum erro a compilação foi realizada com sucesso!
E podemos encontrar o um arquivo novo 'a.out' sera já o seu programa compilado.
Execute o seu programa com o comando abaixo:

*./a.out*

Será mostrada na tela:

*Hello Word!*


O computador vai ler todo seu codigo em '00000' e '111111'.

# Scratch;

Voce consegue dar instruções...

# Expressões Booleanas

Verdadeiro / Falso
True / False

numero1 > numero2

 true and  true = true
 false and true = false
 true and false = false

 
Aula 1.0

# Semana 1

C;
Código;
Compiladores;
GCC;
Funções;
Comentários;
Output padrão;
Operadores aritméticos;
Associatividade;
Variáveis locais;
Primitivos;
Casting;
Input padrão;
Bibliotecas;
Expressões booleanas;
Condições;
Loops.

# Semana 1 > C;

Linguagem C é de baixo nível, pois trabalha com alocação de memória.

Exemplo:

#include <stdio.h>

int
main(void)
{
        printf("Hello Word!\n");
}

**Instruções**

printf("O hai\n");

**Loops > While**: Enquando a condição for verdadeira faça isso...

Exemplo:

while (true)
{
        printd("O hai!\n");
}

**Loops > For**: Estado para iniciar variaveis.

for (int i = 0; i < 10; i++)
{
        printd("O hai!\n");
}

**Arrays**: É listas de coisas para guardar o que quiser, exemplo guardar lista de inteiro, frutas, alunos e etc.

.string = Indica que meu array sera do tipo string.
.[] = indico o numero de coisas que vou guardar dentro do meu array.
.inventory[0] = Acessar o elementro do array, cosultando o primeiro elemento do indice.

string inventory[1];
inventory[0] = "Orange";

# Como fazer um programa:

1. nano hello.c
        Serve para voce criar ou editar.

2. gcc -o hello hello.c
        Faz a compilação do nosso codigo e permite atribuir um nome ao seu programa apos o '-o'.

3. ./hello
        Executa o nosso codigo compilado.

4. make hello
        Faz a compilação do seu codigo a mesma coisa que o 'gcc' o make facilita para voce a compilação. 

5. Makefile
        Existe um arquivo **Makefile** que podemos criar e colocar dentro da pasta onde esta nosso codigo e apos executar o make ele usa o compiado que esta parametrizado dentro do makefile.
        Exemplo do conteudo:
        
        CC = gcc
        CFLAGS = -ggfb -std=c99 -Wall -Werror -Wformat=0
        LIBS = -lm -lcc50
        %: %.c
           $(CC) $(CFLAGS) -o $@ $@.c $(LIBS)
           
# Funções

São executar pelo sinal '()' abaixo segue alguns exemplos:

main ... é função
printf

**Bibliotecas do CC50:**

GetChar: ...uma letra do alfabeto
GetDouble: Uso o dobro da memoria e tem uma aproximacao melhor que o float.
GetFloat: ...para um numero de pontos flutuantes decimais. Exemplos 0,2, 0,5 e etc...
GetInt: .. para o usuario um numero.
GetLonglong: ... Armazena grnade quantidade de numeros
GetString: ... para digitar um texto

**printf**

%c = caracteres
%d = digitos inteiros
%f = numeros decimas
%lld = digitos numeors muito grande
%s = strings
           
**Biblioteca CC50**

#include <cc50.h>
#include <stdio.h>

int
main()
{
        string name = "Adriano";
        printf("O Ola, %s!\n", name);
}

# Use o linux para esse ambiente

. Pode se usar Linux DualBoot com o windows
. Caso desejar use uma VirtualBox

# 

           
        







