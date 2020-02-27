# Professor-Organizando-um-time-de-basquete.
Este repositório é para estudantes em Python, para possam aumentar conhecimentos ajudar outros integrantes no rumo da programação 
## Sobre o projeto:

- Este projeto é apenas uma prática de um estudante em Python.

- Ele vai conter nomes aleatórios, idades aleatórias durante execução do projeto.

- Terá (libs) e como está ideia apareceu.

- Estrutura algoritmizada.

## Como surgiu a ideia?

- Ideia surgiu através de uns desafios que estava assistindo no youtube. (Canal: Curso em vídeo)

- Logo após está ideia surgir pensei em muitas maneiras de dar  inicio nela.

## Questão do projeto

- Um professor de "ED.F" decidiu organizar um jogo de basquete durante ás férias. Foi comparecida 3 salas, e
apresentado apenas 15 alunos de cada sala, abaixo do que professor esperava. Sabendo que uma equipe de basquete
são permitidos apenas 5 jogadores por equipe. Mostre na tela quantas equipes estão presentes.
Quantia de pontos será de 40 pontos, identifique cada jogador com seu nome, mostre quantos pontos ele fez
e qual sua posição.

## Entrada de Dados:

- Importação de bibliotecas.

#Entrada de dados da biblioetcas:

import random
import math

#Dados da primeira equipe:

print('Sala 1!'
      ' Um passo a frente!')
alunos = int(input('Digite quantos alunos estão presentes: '))

##Entrada de dados do tipo str(), int() e bool().

#Abaixo será entrada de alguns dados como :(Str, int, float, bool)

aluno1 = str(input('Digite nome do aluno: '))
aluno2 = str(input('Digite nome do próximo aluno: '))
aluno3 = str(input('Digite nome do próximo aluno: '))
aluno4 = str(input('Digite nome do próximo aluno: '))
aluno5 = str(input('Digite nome do próximo aluno: '))

#Idade dos alunos:

aluno1 = int(input('Digite idade do aluno: '))
aluno2 = int(input('Digite idade do próximo aluno: '))
aluno3 = int(input('Digite idade do próximo aluno: '))
aluno4 = int(input('Digite idade do próximo aluno: '))
aluno5 = int(input('Digite idade do próximo aluno: '))

#Número de cada aluno:

lista = [aluno1, aluno2, aluno3, aluno4, aluno5]
random.shuffle(lista)
print('Ordem de cada número é: ')
print(lista)
