# VisualGProgs

Algoritmo "semnome"

Var
   numero : inteiro
   resultado : inteiro
   resto : real
   P3:real
   P2:real
   P1:real


Inicio
      ESCREVA ("Digite sua primeira base decimal: ")
      LEIA (numero)

      resultado <- numero \ 16
      resto <- numero % 16

      ESCREVAl ("1 - ",resto, " RES=",resultado)
      P3 <- RESTO

      SE (resultado >= 16) ENTAO
         resto <- resultado % 16   //inverti a ordem com a linha abaixo
         resultado <- resultado \ 16
         P2 <- RESTO

         ESCREVAl ("2 - ",resto, " RES=",resultado)
         SE (resultado >= 16) ENTAO
           resultado <- resultado \ 16
           resto <- resultado % 16
           ESCREVAl ("3 - ",resto, " RES=",resultado)
           P1 <- RESTO
         SENAO
           ESCREVAL ("3X - ",resultado)
           P1 <- RESULTADO
         FIMSE
      SENAO
          P2 <- RESULTADO

      FIMSE



      ESCREVAL("RESUMO: -----------------------")

      SE(P1 < 10) ENTAO
        ESCREVA(P1)
      SENAO
         SE(P1 = 10) ENTAO
          ESCREVA("A")
         FIMSE
         SE(P1 = 11) ENTAO
          ESCREVA("B")
         FIMSE
         SE(P1 = 12) ENTAO
          ESCREVA("C")
         FIMSE
         SE(P1 = 13) ENTAO
          ESCREVA("D")
         FIMSE
         SE(P1 = 14) ENTAO
          ESCREVA("E")
         FIMSE
         SE(P1 = 15) ENTAO
          ESCREVA("F")
         FIMSE
      FIMSE

      SE(P2 < 10) ENTAO
        ESCREVA(P2)
      SENAO
         SE(P2 = 10) ENTAO
          ESCREVA("A")
         FIMSE
         SE(P2 = 11) ENTAO
          ESCREVA("B")
         FIMSE
         SE(P2 = 12) ENTAO
          ESCREVA("C")
         FIMSE
         SE(P2 = 13) ENTAO
          ESCREVA("D")
         FIMSE
         SE(P2 = 14) ENTAO
          ESCREVA("E")
         FIMSE
         SE(P2 = 15) ENTAO
          ESCREVA("F")
         FIMSE
      FIMSE

      SE(P3 < 10) ENTAO
        ESCREVA(P3)
      SENAO
         SE(P3 = 10) ENTAO
          ESCREVA("A")
         FIMSE
         SE(P3 = 11) ENTAO
          ESCREVA("B")
         FIMSE
         SE(P3 = 12) ENTAO
          ESCREVA("C")
         FIMSE
         SE(P3 = 13) ENTAO
          ESCREVA("D")
         FIMSE
         SE(P3 = 14) ENTAO
          ESCREVA("E")
         FIMSE
         SE(P3 = 15) ENTAO
          ESCREVA("F")
         FIMSE
      FIMSE

Fimalgoritmo
