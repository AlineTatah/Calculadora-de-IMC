# Calculadora-de-IMC
Programa em Python para calcular IMC!

altura=float(input('Qual é a sua altura?'))
peso=float(input('Qual é o seu peso?'))


IMC=(peso / pow(altura , 2))

print(f'O IMC é de : {IMC:,.2f}')


if IMC <= 18.4 :
  print('Magreza')

elif IMC >=18.5 and IMC <=24.9 :
  print('Normal', )

elif IMC >=25 and IMC <=29.9 :
  print('Sobrepeso')

elif IMC >=30 and IMC <=39.9 :
  print('Obesidade grau 1')

else:
    print('Obesidade grau 2')

