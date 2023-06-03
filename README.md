# basicportugol
Se então no portugol. if then in portugol.
Algoritmo "abc"
// Disciplina   : [Linguagem e Lógica de Programação]
// Professor   : Antonio Carlos Nicolodi 
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 26/05/2023
Var
// Seção de Declarações das variáveis 
      nome:caractere
      hora:inteiro
      msg:caractere
Inicio
// Seção de Comandos, procedimento, funções, operadores, etc... 
     escreva ("Digite seu nome:")
     leia (nome)
     escreva ("Digite a hora atual:")
     leia (hora)
     
     se (hora >0) e (hora<12) então
     escreva ("Bom dia ",nome)
     senao (
     se (hora>=12) e (hora<18) então
     escreva ("Boa tarde ",nome)
     senao
     se (hora>=18) e (hora<=24) então
     escreva ("Boa noite ",nome," são",hora," horas")
     fimse
     fimse
     fimalgoritmo
