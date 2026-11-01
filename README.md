# Calculadora-em-python


###


def calculadora():
    print("1. Soma (+)")
    print("2. Subtração (-)")
    print("3. Multiplicação (*)")
    print("4. Divisão (/)")
    
    opcao = input("Escolha a operação (1/2/3/4): ")
    
    num1 = float(input("Digite o primeiro número: "))
    num2 = float(input("Digite o segundo número: "))
    
    if opcao == '1':
        print(f"Resultado: {num1 + num2}")
    elif opcao == '2':
        print(f"Resultado: {num1 - num2}")
    elif opcao == '3':
        print(f"Resultado: {num1 * num2}")
    elif opcao == '4':
        if num2 != 0:
            print(f"Resultado: {num1 / num2}")
        else:
            print("Erro: Divisão por zero!")
    else:
        print("Opção inválida!")
calculadora()
###
