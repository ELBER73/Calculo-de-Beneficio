# Calculo-de-Beneficio
Como calcular salario com INSS
Algoritmo "CalculoBeneficio"

Var
// Seção de Declarações das variáveis 
      Nome: Caractere
      Sal, NSal: Real
      Dep: Inteiro

Inicio
// Seção de Comandos, procedimento, funções, operadores, etc... 
       Escreva ("Qual o nome do Funcionário? ")
       Leia (Nome)
       Escreva ("Qual o salario do Funcionario? ")
       Leia (Sal)
       Escreva ("Qual é a quantidade de dependentes? ")
       Leia (Dep)
       Escolha Dep
               Caso 0
                     NSal <- sal + (Sal*5/100)
               Caso 1,2,3
                     NSal <- sal + (Sal*10/100)
               Caso 4,5,6
                     NSal <- sal + (Sal*15/100)
               OutroCaso
                     NSal <- sal + (Sal*18/100)
                     
       FimEscolha
       EscrevaL ("O novo salario de ", Nome, " será de R$ ", NSal:5:2)
Fimalgoritmo
