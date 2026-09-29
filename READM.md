# ***Calculadora de Média***
***cálculo da nota1 e nota2, e resultado da média***
***

## **tecnologia utilizada**
**Python 3.13.2**
***

### Como instalar e Executar
Você precisa de um sistema (De sua escolha), ou compilador online
***

#### Exemplo de código
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2

print("=== Sistema de Notas do Aluno ===")
n1 = float(input("Digite a primeira nota:"))
n2 = float(input("Digite a segunda nota:"))
media = calcular_media(n1, n2)
print(f"A media final é: {media:.2f}")

if media >= 7.0:
    print("Status: Aprovado!")
else:
    print("Status: Reprovado.")
***

##### ****Vinícius dos Santos****