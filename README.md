# Exercicio040.py

n1 = float(input('nota 1: '))
n2 = float(input('nota 2: '))
media = (n1 + n2)/2

print('{:.1f} + {:.2f} = {:.2f}'.format(n1,n2,media))
if 7 > media >= 6 :
    print('Recuperação')
elif media < 6:
    print('reprovado')
else:
    print('Aprovado')
