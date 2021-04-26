## Exercício 3

```
Faça um cadastro com nome, ano de nascimento e salário.
Mostre na tela as cores e uma ficha com os dados inseridos
```

```
fun main(){

     println("Digite o seu nome:")
     var nome:String = readLine()!!

    println("Digite o ano de seu nascimento (4 dígitos):")
    var ano = readLine()!!.toInt()

    println("Digite seu salário:")
    var salario = readLine()!!.toFloat()

    // Imprimindo a ficha com cor

    println("${MAGENTA}----------- FICHA FUNCIONAL -----------")
    println("$nome")
    println("$ano")
    println("R$ ${salario.format(2)}")
    print("----------------------------------------")
}
// função para usar o float com 2 casas decimais
fun Float.format(digits: Int) = "%.${digits}f".format(this)
```

