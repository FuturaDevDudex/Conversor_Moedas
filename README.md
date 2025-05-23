# Conversor_Moedas

O desafio 010 é para criar um programa que leia quanto dinheiro uma psoa tem na carteira e mostre quantos dólares ela pode comprar. 

carteira = int(input('Quanto de dinheiro, você tem na carteira? '))  Nesta parte do código, ira apresentar a mensagem entre aspas simples, fazendo com que o usuário digite um valor. A função float() e responsável por números reais e ponto flutuante, e input() é a informação de texto, que apresenta para o usuário.

dolar = carteira / 5.97  O valor que está na variável 'carteira' é divido por 5.97 que consiste no valor do dolar atualmente. 

print (f'com R${carteira} você poder comprar US${dolar:.2f}')  Print() A função é utilizada para apresentar as informações na tela do usuário, juntamente com outras variáveis na tela. Como por exemplo a variáve 'carteira' e 'dolar'. 
