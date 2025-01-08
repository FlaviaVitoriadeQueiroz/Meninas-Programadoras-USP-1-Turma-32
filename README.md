# Meninas-Programadoras-USP-1-Turma-32
Meus códigos/respostas do curso de python da USP

Conceitos da primeira aula:
linha = input() #função de entrada
print(linha) #saida dos dados
Exemplo: nomeUser = input('qual o seu user do instagram?')
         print(nomeUser)
#números inteiros = int
#números decimais = float
Exemplo: velocidade = float (input())
         dist = float (input())
         tempo = dist/velocidade
         print (tempo)

Exercícios da primeira semana:
Exercício 1- Nomes alternativos
Consiste em alterar a ordem dois nomes
firstName= input()
middleName= input()
lastName= input()
print(firstName, middleName, lastName)
print(firstName, lastName)
print(lastName+',',firstName)

Exercício 2- Brincando com sequências de caracteres
letra1= input()
letra2= input()
cs1= input()
cs2= input()
ni= int (input())
soma1= letra1+cs1
soma2= letra2+cs2
soma3= (soma1+soma2) * ni
print(soma1)
print(soma2)
print(soma3)

Exercício 3- O proxímo, o anterior, o dobro, a metade
#o proxímo:
n = int(input())
proximo= n + 1
print(str(proximo))
#o anterior:
n = int(input())
anterior= n - 1
print(str(anterior))
#o dobro:
n = int(input())
dobro= n *2
print(str(dobro))
#a metade:
n = int(input())
metade= n /2
print('%.1f' % metade)
#ou
n= int (input())
resultado= n/2
print (f"{resultado:.1f}")

Exercício 4- Decimais a moda antiga
valor = float (input ())
print ('%.2f' % valor)
print ('%.4f' % valor)
print ('%.6f' % valor)
print ('%.8f' % valor)
print ('%.10f' % valor)
#o f serve para formatar, por exemplo, mostrar 10.15 em vez de 10.555555

Exercício 5- Soma, subtração, multiplicação, divisão, módulo, divisão inteira e potência
v1= int (input())
v2= int (input())
soma= v1+v2
sub= v1-v2
multi= v1*v2
div= v1/v2
mod= v1%v2
divint= v1//v2
pot= v1**v2
print(int (soma))
print(int (sub))
print(int (multi))
print('%.2f' % div)
print(int (mod))
print(int (divint))
print(int (pot))

Exercício 6- Pin
niver= int (input())
namoro= int (input())
pin= niver+namoro
print(pin)

Exercício 7- A Compra Questionável
dinemb= int (input())
tcc= int (input())
saldonaconta= dinemb-tcc
print(int (saldonaconta))

Exercício 8- O aumento no salário
salario= int (input())
paumento= int (input())
final= (paumento/ 100)* salario
print(final)

Exercício 9- O salário reajustado
salario= int (input())
paumento= int (input())
faumento= ((paumento*salario)/100)
novosalario= salario+faumento
print(novosalario)

Exercício 10- Minuteira
nh= int (input())
nm= int (input())
minutos= nh*60
tempototal= minutos + nm
print(tempototal)

Exercício 11- Horas e minutos
total_minutos = int(input())
horas = total_minutos // 60
minutos = total_minutos % 60
print(f"{total_minutos}min = {horas}h{minutos}min")

Exercício 12- Proporções
lista1= int (input())
lista2= int (input())
lista3= int (input())
lista4= int (input())
erl1= int (input())
erl2= int (input())
erl3= int (input())
erl4= int (input())
porcentagem1= (erl1*100)/lista1
porcentagem2= (erl2*100)/lista2
porcentagem3= (erl3*100)/lista3
porcentagem4= (erl4*100)/lista4
print('%.1f' % porcentagem1)
print('%.1f' % porcentagem2)
print('%.1f' % porcentagem3)
print('%.1f' % porcentagem4)

Exercício 13- Juros Compostos
valor_inicial = float(input())
taxa_juros = float(input())
taxa_juros_decimal = taxa_juros
pagamento_1 = valor_inicial * (1 + taxa_juros_decimal) ** 1
pagamento_2 = valor_inicial * (1 + taxa_juros_decimal) ** 2
pagamento_3 = valor_inicial * (1 + taxa_juros_decimal) ** 3
print(f"{pagamento_1:.2f}")
print(f"{pagamento_2:.2f}")
print(f"{pagamento_3:.2f}")

Exercício 14- Porcentagem
vi= float (input())
porcentagem_dada= int (input())
resultado= (vi* porcentagem_dada)/100
print("%.2f" % resultado)

Exercício 15- Idade
nasceu= int(input())
morreu= int(input())
vida= morreu-nasceu
print(vida)

Exercício 16- Cicloa para uma boa noite de sono
horas = int (input())
minutos = int (input())
min = (horas * 60) + minutos
ciclos = min / 90
if min >= 450 and min <= 540:
  print(f"5 ciclos indica uma boa noite de sono")
else:
  print(f"4 ciclos não indica uma boa noite de sono")
