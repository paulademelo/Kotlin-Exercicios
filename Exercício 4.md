## Exercício 4

```
/*
* Exercício 04 : o usuário irá digitar 2 números e o programa
* irá fazer as seguintes operações:
* soma
* subtração
* divisão
* multiplicação
* módulo
* maior valor
* menor valor
*/
package exercicios
import kotlin.math.max
import kotlin.math.min
fun main() {

    println("Digite o primeiro número:")
    var n1 = readLine()!!.toInt()
    println("Digite o segundo número:")
    var n2 = readLine()!!.toInt()

    println("${VERMELHO}------------------------------------------")
    println("       DOIS VALORES")
    println("------------------------------------------")

    println("${RESET}Número 1 : ${VERDE} $n1")
    println("${RESET}Número 2: ${VERDE} $n2")

    println("${VERDE}----------------RESULTADOS--------------------")
    println("${VERDE}Soma: ${AZUL} $n1 + $n2 = ${AMARELO}${n1 + n2} ")
    println("${VERDE}Subtração: ${AZUL} $n1 - $n2 = ${AMARELO} ${n1 - n2}")
    println("${VERDE}Multiplicação: ${AZUL} $n1 * $n2 = ${AMARELO} ${n1 * n2}")
    println("${VERDE}Divisão: ${AZUL} $n1 / $n2 = ${AMARELO} ${n1.div(n2.toFloat())}")
    println("${VERDE}Módulo: ${AZUL} $n1 % $n2 = ${AMARELO} ${n1 % n2}")
    println("${VERDE}O maior valor entre ${AZUL}$n1 ${VERDE}e ${AZUL}$n2 ${VERDE}é: ${AMARELO}${max(n1, n2)} ") //seleciona o maior valor
    println("${VERDE}O menor valor entre ${AZUL}$n1 ${VERDE}e ${AZUL}$n2 ${VERDE}é: ${AMARELO}${min(n1, n2)}") // seleciona o menor valor)
    println("${VERDE}----------------------------------------------")

}
```