# Operadores em Java (02/07)

## Operadores em Java

Os operadores são elementos fundamentais na programação, usados para realizar operações em variáveis e valores. Em Java, eles podem ser classificados em várias categorias, como operadores de atribuição, operadores aritméticos, operadores lógicos e o operador ternário. Vamos entender cada um deles com mais detalhes.

### Operadores de Atribuição

Os operadores de atribuição são utilizados para atribuir valores às variáveis. O operador de atribuição mais básico é o “=”, igual. Com ele, você pode atribuir diretamente um valor a uma variável. Por exemplo:

```
    int x = 10; // atribui o valor 10 à variável x
```

Além do operador de atribuição simples, Java também oferece operadores de atribuição compostos. Estes combinam uma operação aritmética ou bit a bit com a atribuição, facilitando operações como somar um valor à variável e depois atualizar essa variável com o novo valor.

Estes são operadores de atribuição composta:

- **```+=```**, mais igual: Adiciona o valor à direita ao valor atual da variável e armazena o resultado na própria variável.

- **```-=```**, menos igual: Subtrai o valor à direita do valor atual da variável e armazena o resultado na própria variável.

- **```*=```**, asterisco igual: Multiplica o valor atual da variável pelo valor à direita e armazena o resultado.

- **```/=```**, barra igual: Divide o valor atual da variável pelo valor à direita e armazena o resultado.

Exemplo:

```
    int x = 5;

    x += 3; // agora, x vale 8 (5 + 3)

    x -= 1; // agora, x vale 7 (8 - 1)

    x = 2; // agora, x vale 14 (7 * 2)

    x /= 2; // agora, x vale 7 (14 / 2)
```

### Operadores Aritméticos

Os operadores aritméticos são usados para realizar operações matemáticas básicas. Em Java, eles incluem:

- 1. **```Adição (+)```**: Soma dois valores. Exemplo: 

```
    int sum = 5 + 3; // sum vale 8
```

- 2. **```Subtração (-)```**: Subtrai o segundo valor do primeiro. Exemplo:

```
    int diff = 5 - 3; // diff vale 2
```

- 3. **```Multiplicação (*)```**: Multiplica dois valores. Exemplo: 

```
    int product = 5 * 3; // product vale 15
```

- 4. **```Divisão (/)```**: Divide o primeiro valor pelo segundo. Exemplo:

```
    int quotient = 9 / 3; // quotient vale 3
```

- 5. **```Módulo (%)```**: Retorna o resto da divisão do primeiro valor pelo segundo. Exemplo:

```
    int remainder = 10 % 3; // remainder vale 1
```

- 6. **```Incremento (++)```**: Aumenta o valor da variável em 1. Exemplo:

```
    int x = 5; x++; // x agora vale 6
```

- 7. **```Decremento (–-)```**: Diminui o valor da variável em 1. Exemplo:

```
    int x = 5; x–-; // x agora vale 4
```

### Operadores Lógicos

Os operadores lógicos são fundamentais na construção de expressões condicionais, permitindo a combinação e manipulação de valores booleanos (true ou false, verdadeiro ou falso respectivamente).

1. **```AND Lógico (&&)```**: Retorna ‘true’ apenas se ambos os operandos forem ‘true’. Caso contrário, retorna ‘false’. Exemplo:

```
    boolean result = (5 > 3) && (8 > 6); // result é true
```

2. **```OR Lógico (||)```**: Retorna ‘true’ se pelo menos um dos operandos for ‘true’. Retorna ‘false’ apenas se ambos forem ‘false’. Exemplo:

``` 
    boolean result = (5 > 3) || (8 < 6); // result é true
```

3. **```NOT Lógico (!)```**: Inverte o valor do operando. Se for ‘true’, torna-se ‘false’, e vice-versa. Exemplo:

```
    boolean result = !(5 > 3); // result é false
```

### Tabelas Verdade

A tabela verdade é uma ferramenta que mostra todas as combinações possíveis de valores para as variáveis em uma expressão lógica e o resultado correspondente, ajudando a entender o comportamento dos operadores lógicos em diferentes cenários.

Para entender melhor como funcionam os operadores lógicos, vejamos as tabelas verdade para os operadores AND e OR:

## Figura 1: Tabelas Verdade. 
![Figura 1: Tabelas Verdade](./imgs/Figura%201%20-%20Tabelas%20Verdade.png)

![Figura 2: Tabelas Verdade](./imgs/Figura%202%20-%20Tabelas%20Verdade.png)

### Operador Ternário

O operador ternário é uma maneira concisa de realizar uma operação condicional, substituindo uma estrutura ‘if-else’. E é um operador muito útil para simplificar expressões condicionais e tornar o código mais legível. Sua sintaxe é:

```
    resultado = condição ? valorSeVerdadeiro : valorSeFalso;
```

- Condição: Uma expressão que retorna **‘true’** ou **‘false’**.

- ValorSeVerdadeiro: O valor que será atribuído a **‘resultado’** se a condição for **‘true’**.

- ValorSeFalso: O valor que será atribuído a **‘resultado’** se a condição for **‘false’**.

Exemplo:

```
    int age = 18;
    String message = (age >= 18) ? “Adult” : “Minor”;
    // message será “Adult” porque a condição é true
```

## 💡 Conteúdo Complementar

**Título:** 11 - Operadores em Java 

**Canal:** Sistema Ativo **Plataforma:** [```YouTube```](https://youtu.be/JFlRIkZBbGI?si=7qfVcmGsUoq40pjA)

**Descrição:** O que são operadores em Java? Em Java, operadores são símbolos ou palavras reservadas usados para realizar operações em valores ou variáveis. Esses operadores podem ser classificados em diferentes categorias, dependendo da operação que realizam.
