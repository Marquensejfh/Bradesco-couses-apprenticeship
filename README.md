# Bradesco-Python-couse-apprenticeship

Random things I learned in Bradesco Python couses. This is a reminder for me 





codigo = 10
salario = 1500.00
nome = "jose"
situacao = True

tipo = type(situacao)

def FSalario():
    print(
    ("\nNome:"),
    nome,
    ("\tSalario:"),
    salario,
    ("\tCodigo:"),
    codigo,
    "\tSituação:",
    situacao,
    "\n",
)


# ===================================
def FAbc():
    A = 5
    B = 15
    C = 20

    print("A == B and B > C :", A == B and B > C)
    print("A < B or B >C :", A < B or B > C)
    print("not A == B :", not A == B)


# ===================================
def FNota():
    notaA = float(input("\nDigite a nota do 1°Trimestre:"))
    notaB = float(input("\nDigite a nota do 2°Trimestre:"))
    notaC = float(input("\nDigite a nota do 3°Trimestre:"))

    MediaFinal = (notaA + notaB + notaC) / 3

    if MediaFinal >=9.0: 
        print ("\n Aprovadoissimo, sua Media foi:",MediaFinal,"Parabens!")
    elif MediaFinal >= 6.0:
        print ("\n Aprovado, sua Media foi:",MediaFinal)
    else :
        print ("\n Reprovado, sua Media foi:",MediaFinal)


# ===================================
def FIdade():

    Idade = 0

    Idade = int(input("\ndigite a idade de uma pessoa:"))
    if Idade > 17:
        print("maior de idade")
    else:
        print("menos de idade")


# ===================================
def FFruta():
    fruta = input("\ndigite uma fruta: ")
    print(fruta)

# ===================================
def F0a20():
    P2=0
    while P2<=15:
        print(P2)
        P2=P2+1 

    for P1 in range(16,21):
        print (P1)
 

# ===================================
opcao = 0
    
print ("\n------------------------------------------------------Menu------------------------------------------------------\n")
print ("\n  \t \t \t \t \t \tEscolha a Funçao: \n \n 1-Funcao Salario \t 2-Funcao ABC \t 3-Funçao nota \t 4-Funçao Idade \t 5-Funçao Fruta \t 6-sair \n")
opcao=int(input("\n Qual a opçao?"))

while opcao != 7:
    print ("\n  \t \t \t \t \t \tEscolha a Funçao: \n \n 1-Funcao Salario \t 2-Funcao ABC \t 3-Funçao nota \t 4-Funçao Idade \t 5-Funçao Fruta \t 6-Funçao de 0 a 20 \t 7-sair \n")
    opcao=int(input("\n Qual a opçao?"))

    if opcao == 1:
        FSalario()
    elif opcao ==2:
        FAbc()
    elif opcao ==3:
        FNota()
    elif opcao ==4:
        FIdade()
    elif opcao ==5:
        FFruta()
    elif opcao ==6:
        F0a20()
    else:
        exit()

