## Exercício 5

```
package exercicios

/*
*Exercício 5 : média estudonauta
*
*/
fun main() {
    println("${VERMELHO}------------------------------------------")
    println("       NOTAS ETUDONAUTA")
    println("------------------------------------------")

    println("${RESET}Digite a primeira nota:")
    var n1 = readLine()!!.toFloat()

    println("Digite a segunda nota:")
    var n2 = readLine()!!.toFloat()

    println("Nota 1: ${VERDE} $n1")
    println("${RESET}Nota 2: ${VERDE} $n2")

    println("${VERDE}----------------RESULTADOS--------------------")
    println("As notas do aluno foram: ${AMARELO} $n1 ${VERDE}e ${AMARELO}$n2")
    println("${VERDE}A média final foi de ${ (n1+n2)/2}")
    println("${VERDE}----------------------------------------------")
}
```