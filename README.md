# Primeiro-Jogo-programa-em-Python

print("bem vindo ao jogo de perguntas")

resposta = str(input("você deseja jogar? "))

resposta = resposta.lower()

if resposta == "sim":
  pass
else:
  quit()

pontos = 0

print("pergunta 1")

resposta_1 = str(input("Qual a capital do Brasil? "))
resposta_1 = resposta_1.capitalize()

if resposta_1 == "Brasilia":
  print("parabens! voce acertou!")
  pontos += 1
else:
  print("Que pena, voce errou.")

print("pergunta 2")

resposta_2 = str(input("Quantos segundos tem 420 minutos? "))

if resposta_2 == "25200":
  print("parabens! voce acertou!")
  pontos += 1
else:
  print("Que pena, voce errou.")

print("pergunta 3")

resposta_3 = str(input("Qual continente vive o Leão? "))
resposta_3 = resposta_3.capitalize()

if resposta_3 == "Africa":
  print("parabens! voce acertou!")
  pontos += 1
else:
  print("Que pena, voce errou.")

print("sua pontuação foi {} de 3".format(pontos))

print("Fim de jogo")