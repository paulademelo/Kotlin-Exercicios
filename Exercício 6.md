## Exercício 6

```
package exercicios

/*
Exercício 06: Cálculo de potência
O usuário irá inserir o valor da base e o expoente, o programa irá calcular a potência.
*/

fun main(){
    println("${VERMELHO}------------------------------------------")
    println("       CÁLCULO DE POTÊNCIA")
    println("------------------------------------------")
    println("${RESET}Digite o valor da base a ser calculada: ")
    var valor = readLine()!!.toDouble()

    println("${RESET}Digite o valor do expoente:")
    var exp = readLine()!!.toDouble()
    var result = Math.pow(valor,exp)

    println("${VERDE}----------------RESULTADOS--------------------")
    println("Calculando ${AMARELO} $valor ${VERDE} elevado a ${AMARELO}$exp")
    println("${VERDE}O resultado é de ${result} ")
    println("${VERDE}----------------------------------------------")
}


```

