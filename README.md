Algoritmo "Conversão"

var
   n, n1: inteiro
   n2, conv: real

inicio
   // Entrada de dados
   escreva("Digite a quantidade de conversões: ")
   leia(n)
   n1 <- 1 // Inicializa o contador

   enquanto (n1 <= n) faca
      escreva("Digite a temperatura em Fahrenheit que deseja converter: ")
      leia(n2)

      // Operação de conversão
      conv <- (5 * (n2 - 32)) / 9

      // Saída de dados
      escreval(n2:0:2, " FAHRENHEIT EQUIVALE A ", conv:0:2, " CELSIUS")

      n1 <- n1 + 1 // Incrementa o contador
   fimenquanto

fimalgoritmo
