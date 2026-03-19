# exercicio3-raciocicinio-algoritmico

#1
```python
import time
import random
numero = random.randint(1, 10)
print("Bem-vindo ao jogo!")
time.sleep(2)
print("Você se encontra em uma floresta, e há dois caminhos em sua frente...")
time.sleep(2)
print("Para prosseguir é necessário escolher um dos caminhos, Esquerda ou Direita")
time.sleep(2)
caminho = input("Qual caminho deseja seguir? (d/e): ").lower()
if caminho == "d":
    print("Ao seguir pelo caminho da direita, é possivel ver uma montanha")
    time.sleep(2)
    escalar = input("Você pode escolher entre escalar a montanha ou voltar, gostaria de escalar? (s/n): ").lower()
    if escalar == "s":
        print("Ao escalar a montanha você encontra uma caverna no topo...")
        time.sleep(2)
        print("Você entra em uma caverna escura e vê um brilho na distância...")
        time.sleep(2)
        print("Ao se aproximar, percebe que é um tesouro...")
        time.sleep(2)
        print("Você tenta voltar para sair da caverna, mas percebe que a saída não existe mais")
        time.sleep(2)
        print("Sua única alternativa é tentar abrir o tesouro, ao se aproximar percebe uma mensagem na parede")
        time.sleep(2)
        print("Para sair da caverna é necessário abrir o tesouro, sendo preciso passar por um teste de sorte")
        time.sleep(2)
        print("O teste de sorte consiste em escolher o número certo entre 1 a 10, sendo possível 3 chances")
        time.sleep(2)
        tentativa = 0
        while tentativa < 3:
                    numeroAleatorio = int(input("Escolha um numero aleatorio entre 1 e 10: "))
                    if numeroAleatorio == numero:
                        print("Parabéns, você acertou o número e conseguiu abrir o tesouro!")
                        time.sleep(2)
                        print("Você venceu!")
                        break
                    else:
                        tentativa += 1
                        if tentativa < 3:
                            print(f"Você errou, restam {3- tentativa} tentativas...")
                        else:
                            print("Você não conseguiu acertar...")
                            time.sleep(2)
                            print("Fim de jogo.")
    else:
        print("Você decide não escalar a montanha e acaba voltando de onde veio")
        time.sleep(2)
        print("Mas ao voltar percebe que o caminho não é o mesmo e acaba se perdendo na floresta...")
        time.sleep(2)
        print("Fim de jogo!")
else:
     print("Ao seguir pelo caminho da esquerda, você se depara com um rio")
     time.sleep(2)
     atravessar = input("Você deseja atravessá-lo? (s/n):")
     if atravessar == "s":
          print("Ao atravessar o rio, você chega em uma vila segura e vive o resto de sua vida lá")
          time.sleep(2)
          print("Fim de jogo!")
     else:
          print("Você decide não atravessar o rio e tenta voltar de onde veio")
          time.sleep(2)
          print("Mas ao voltar percebe que o caminho não é o mesmo e acaba se perdendo na floresta...")
          time.sleep(2)
          print("Fim de jogo!")
```

#2

