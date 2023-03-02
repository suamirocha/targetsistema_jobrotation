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
def verifica_fibonacci(num):
    """
    Função que recebe um número e verifica se ele pertence à sequência de Fibonacci.
    """
    a, b = 0, 1
    while b < num:
        a, b = b, a + b
    return b == num

# Exemplo de uso:
num = int(input("Digite um número: "))
fibonacci = verifica_fibonacci(num)
if num in fibonacci:
    print(f"O número {num} pertence à sequência de Fibonacci!")
else:
    print(f"O número {num} não pertence à sequência de Fibonacci.")
```    
    
Explicando o código: a função verifica_fibonacci recebe um número e verifica se ele pertence à sequência de Fibonacci, utilizando um loop while para calcular a sequência até que um valor igual ou maior ao número informado seja encontrado. Ao chegar nessa condição, o loop é interrompido e o valor de b é comparado ao número informado. Se forem iguais, o número pertence à sequência de Fibonacci, caso contrário, não pertence.

No exemplo de uso, o usuário informa um número, a sequência de Fibonacci é calculada até esse número e então é verificado se o número informado pertence à sequência ou não. É importante notar que a função verifica_fibonacci calcula a sequência até um valor maior ou igual ao número informado, para garantir que a sequência esteja completa até esse valor e possa ser verificada corretamente.

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
f) 200

---

- 4 Dois veículos (um carro e um caminhão) saem respectivamente de cidades opostas pela mesma rodovia. O carro de Ribeirão Preto em direção a 
Franca, a uma velocidade constante de 110 km/h e o caminhão de Franca em direção a Ribeirão Preto a uma velocidade constante de 80 km/h. Quando eles se 
cruzarem na rodovia, qual estará mais próximo a cidade de Ribeirão Preto?

### Resolução:


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
