# Calculadora em Python

Este é um projeto simples de uma calculadora feita em Python, como parte dos meus estudos de lógica de programação.

## Funcionalidades:
- Soma
- Subtração
- Multiplicação
- Divisão

## Como executar:
1. Instale Python na sua máquina
python calculadora.py

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
