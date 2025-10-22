# Atividade-Loop

#Desafio 1

n = int(input('Digite uma nota, entre zero e dez: '))
 while n > 10 or n < 0:
    n = int(input("Errou, tente dnv: "))
 print("boa")

#Desafio 2

user = input("Digite o usuario: ")
senha = input("Digite a senha: ")

for senha in user:
    print("Tente novamente")
    user = input("Digite o usuario: ")

    senha = input("Digite a senha: ")

#Desafio 3

user = input('Digite o seu nome: ').strip()
while len(user) < 3:
    user = input('Nome menor que 3 caracteres. Tente novamente: ').strip()
print ('Nome aceito.')

idade = int(input('Digite sua idade: '))
while idade < 0 or idade > 150:
    idade = int(input('Idade não aceita. Tente novamente: '))
print('Idade aceita.')

salario = int(input('Digete seu salário: '))
while salario <= 0:
    salario = int(input('Salário não válido. Tente novamente: '))
print ('Salário aceito.')

sexo = input('Digite seu sexo(m/f): ')
while sexo not in ['m', 'f']:
    sexo = input('Sexo inválido. Tente novamente: ')
print ('Sexo aceito.')

estado_civil = input('Digite seu estado civil: ')

while estado_civil not in ['s', 'c', 'v', 'd']:
    estado_civil = input('Estado civil inválido. Tente novamente: ')
print ('Estado civil aceito.')
