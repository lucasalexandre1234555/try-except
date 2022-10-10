print("Digite dois números, e a divisão será feita.")
print("Tecle \"q\" para sair.")
while True:
    primeiro_numero = input("\nPrimeiro número: ")
    if primeiro_numero == "q":
        break
    segundo_numero = input("Segundo número: ")
    try:
        resposta = int(primeiro_numero) / int(segundo_numero)
    except ZeroDivisionError:
        print("Você não pode dividir por 0!")
    except ValueError:
        print("digite apenas numeros!!")
    else:
        print(resposta)
