print('+ Adição' )
print('- Subtração' )
print('* Multiplicação' )
print('/ Divisão' )
a = int(input('Digite o primeiro valor a ser utilizado: '))
b = int(input('Digite o segundo valor a ser utilizado: '))
operacao = input('Informe qual operador deseja utilizar?')

if (operacao == '+'):
    res = a + b
    print(f'Resultado {a} + {b} = {res}')
elif (operacao == '-'):
    res = a - b
    print(f'Resultado {a} - {b} = {res}')
elif (operacao == '*'):
    res = a * b
    print(f'Resultado {a} * {b} = {res}')
elif (operacao == '/'):
    res = a / b
    print(f'Resultado {a} / {b} = {res}')
