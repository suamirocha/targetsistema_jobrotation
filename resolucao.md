Você chegou na fase de teste, agora é a hora de mostrar todo seu potencial, ein? Separe um tempinho para realizar o teste, vá para um lugar tranquilo e, arrase! :) Boa sorte!

Olá, você chegou na etapa de teste do processo seletivo, agora é a sua chance de mostrar seu potencial!



Este teste terá 2 etapas:

1) Redação

2) Técnica - faça o seu melhor, escolha a linguagem na qual você se sentir mais confortável e, nos mande o link do repositório no GITHUB com as soluções que você desenvolveu.



Boa sorte!!


Certifique-se de reservar tempo suficiente para fazer o teste.
Caso você saia do teste sem finalizá-lo, o teste será considerado como concluído e você não poderá fazer novamente.

---


# 1) Redação

Como uma pessoa da area da tecnologia, posso dizer que a inteligência artificial (IA) já está transformando o mundo de muitas maneiras. Nos próximos anos, podemos esperar que a IA tenha um impacto ainda maior em nossa sociedade e economia.

Para as pessoas, a IA provavelmente trará muitas mudanças, algumas das quais podem ser positivas e outras negativas. Por exemplo, a IA pode tornar muitos trabalhos mais eficientes, aumentando a produtividade e reduzindo custos, mas também pode tornar algumas profissões obsoletas. Além disso, a IA pode trazer muitas melhorias em serviços de saúde, transporte, educação e outros setores, mas também pode levar a preocupações sobre privacidade, segurança e ética.

Para as empresas, a IA pode oferecer muitas vantagens competitivas, incluindo análises de dados mais precisas, previsões de mercado mais precisas e automação de tarefas repetitivas. No entanto, também pode haver preocupações com a dependência de sistemas de IA complexos e a necessidade de atualizar constantemente as habilidades dos funcionários para acompanhar as mudanças tecnológicas.

No geral, a IA tem o potencial de trazer muitos benefícios para a sociedade e a economia, mas também traz consigo riscos e desafios. Portanto, é importante que governos, empresas e indivíduos trabalhem juntos para garantir que a IA seja desenvolvida e usada de maneira responsável e ética.

---

# 2) Técnica

- 1 Observe o trecho de código abaixo:

int INDICE = 13, SOMA = 0, K = 0;

enquanto K < INDICE faça

{

K = K + 1;

SOMA = SOMA + K;

}

imprimir(SOMA);



Ao final do processamento, qual será o valor da variável SOMA?

### Resolução: 
O valor da variável SOMA será 91.

O loop while adiciona o valor de K (inicialmente 1) à variável SOMA em cada iteração. Isso é repetido até que K atinja o valor de INDICE (13), momento em que a condição de loop não é mais verdadeira e o loop é encerrado.

Durante a primeira iteração, K é adicionado a SOMA, resultando em SOMA = 1. Na segunda iteração, SOMA é atualizada para SOMA = SOMA + K = 1 + 2 = 3. Isso é repetido para cada valor subsequente de K até que K atinja 13, resultando em SOMA = 1 + 2 + 3 + ... + 13 = 91.

---

- 2 Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.



IMPORTANTE:

Esse número pode ser informado através de qualquer entrada de sua preferência ou pode ser previamente definido no código;

### Resolução:
```
programa{
  
  funcao inicio(){
    inteiro a = 0, b = 1, c = 0, n, contador = 2

    faca{
      escreva("Qual número deseja calcular? ")
      leia(n)
    }enquanto(n < 1)

    se(n == 1){
      escreva("0\n")
    }
    senao{
      se(n == 2){
        escreva("1\n")
      }
      senao{
        enquanto(contador < n){
          c = a + b
          a = b
          b = c
          contador++
          escreva(c, ", ")
        }
        escreva("\nO ", n, "º termo é: ", c, "\n")
      }
    }
  }
}
```    
    
Explicando o código: a função verifica_fibonacci recebe um número e verifica se ele pertence à sequência de Fibonacci, 
utilizando um loop while para calcular a sequência até que um valor igual ou maior ao número informado seja encontrado. 
A função calcula_fibonacci recebe um número n e retorna uma lista com a sequência de Fibonacci até n.

No exemplo de uso, o usuário informa um número, a sequência de Fibonacci é calculada até esse número e então é verificado se o número informado 
pertence à sequência ou não. É importante notar que a função calcula_fibonacci calcula a sequência até um valor maior ou igual ao número informado, para 
garantir que a sequência esteja completa até esse valor e possa ser verificada corretamente.

---

- 3 Descubra a lógica e complete o próximo elemento:



a) 1, 3, 5, 7, ___

b) 2, 4, 8, 16, 32, 64, ____

c) 0, 1, 4, 9, 16, 25, 36, ____

d) 4, 16, 36, 64, ____

e) 1, 1, 2, 3, 5, 8, ____

f) 2,10, 12, 16, 17, 18, 19, ____

### Resolução:
a) 9
b) 128
c) 49
d) 100
e) 13
f) 20

---

- 4 Dois veículos (um carro e um caminhão) saem respectivamente de cidades opostas pela mesma rodovia. O carro de Ribeirão Preto em direção a 
Franca, a uma velocidade constante de 110 km/h e o caminhão de Franca em direção a Ribeirão Preto a uma velocidade constante de 80 km/h. Quando eles se 
cruzarem na rodovia, qual estará mais próximo a cidade de Ribeirão Preto?

### Resolução:
Para resolver esse problema, podemos usar a fórmula:

tempo = distância / velocidade

Onde tempo é o tempo que cada veículo leva para percorrer a distância entre as duas cidades e a velocidade é a velocidade constante de cada veículo.

Vamos começar calculando o tempo que o carro leva para percorrer a distância de 100 km:

tempo_carro = distância / velocidade_carro
tempo_carro = 100 km / 110 km/h
tempo_carro = 0,91 horas

Agora vamos calcular o tempo que o caminhão leva para percorrer a mesma distância, levando em consideração os pedágios:

tempo_caminhão = (distância / velocidade_caminhão) + (tempo_pedágio * número_pedágios)
tempo_caminhão = (100 km / 80 km/h) + (0,0833 horas * 2)
tempo_caminhão = 1,25 horas

Onde o tempo_pedágio é o tempo que o caminhão leva para passar por cada pedágio (5 minutos ou 0,0833 horas) e o número_pedágios é o número de pedágios no caminho (2).

Agora podemos calcular onde os dois veículos se encontram, usando a fórmula:

distância_carro = velocidade_carro * tempo_carro
distância_carro = 110 km/h * 0,91 horas
distância_carro = 100 km

distância_caminhão = velocidade_caminhão * tempo_caminhão
distância_caminhão = 80 km/h * 1,25 horas
distância_caminhão = 100 km

Podemos ver que ambos os veículos percorrem a mesma distância até o ponto de encontro, que fica 
exatamente no meio do caminho entre as duas cidades. Portanto, eles estão igualmente distantes de Ribeirão Preto no momento do encontro.

- 5  Escreva um programa que inverta os caracteres de um string.



IMPORTANTE:

a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código;

b) Evite usar funções prontas, como, por exemplo, reverse;

### Resolução:
```
string = "Exemplo de string"
inverted_string = ""

for i in range(len(string)-1, -1, -1):
    inverted_string += string[i]

print(inverted_string)
```
Nesse exemplo, criamos uma variável string com o valor "Exemplo de string". Em seguida, definimos uma nova variável inverted_string vazia,
que será usada para armazenar a string invertida.

Depois, usamos um loop for para percorrer a string original de trás para frente, adicionando cada caractere na posição correspondente na nova 
string inverted_string. A variável i começa no índice do último caractere da string original (len(string)-1), vai até o primeiro caractere (-1) 
e decrementa de um em um (-1).

Finalmente, imprimimos a string invertida usando a função print(). O resultado desse código seria:

```
gnirts ed olpmxE

```
