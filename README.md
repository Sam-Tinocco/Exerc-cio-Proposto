'''ENUNCIADO: Um aluno iniciou seus estudos em geometria plana e, para 
validar se suas respostas estão corretas, solicitou sua ajuda.
Construa um programa para auxiliar esse aluno.

DICAS - Fórmula: Area = (base * altura) / 2

AUTORA: Sâmara Tinoco
DATA: 23/10/2025
FONTE: EP_Exer01Pag50.py
'''
print("\nInicio!")
## Declaração e Entrada de Dados
##vlrRaio = float(input("\nDigite informando o raio da área: "))
vlrBase = float(input("Digite informando o valor da Base do Triângulo: "))
vlrAltura = float(input("Digite informando o valor da Altura do Triângulo: "))
vlrArea = (vlrBase * vlrAltura) / 2
print(f"\nA área do triângulo é = {vlrArea: .2f}")
print("\nFim!")
