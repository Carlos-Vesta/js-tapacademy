
# MICROPROCESSADOR
Um Microprocessador apenas entende 0's e 1's.
Entende códigod Binários
Entende Linguagem de Máquina (Machine Level Language - MLL)

# PROGRAMA
Um programa é uma colecção de instruções.

O processo de criar colecção de instruções chama-se PROGRAMAR.

# COMPILADOR (COMPILER)
Compilador é um software que recebe uma linguagem de Alto Nível (HIGH LEVEL LANGUAGE - HLL) como entrada, e converte linha a linha em Linguagem de Máquina (MLL).

- Compilar é o processo de converter todo o código em linguagem de máquina.
- Para compilar nós usamos um software chamado compilador.
- Comparado a interpretação, compilar é mais rápido na execução
- Ex: C, Java, C++

# INTERPRETADOR (INTERPRETER)
Interpretador é um sosftware que recebe uma linguagem de Alto Nível (HIGH LEVEL LANGUAGE - HLL) como entrada, e converte linha a linha em Linguagem de Máquina (MLL).

- Interpretar é o processo de converter o código em linguagem de máquina linha por linha.
- Para interpretar nós usamos um software chamado interpreter.
- Comparado a compilação, interpretar é lento na execução
- Ex: Python, Javascript

# JAVASCRIPT
É possível rodar o javascript de duas formas:

    ** Modo Script (Script Mode)
        - O código é escrito em um ficheiro e salvo antes de ser executado;
        - É usado para escrever e executar programas extensos (grandes);
        - Requere salvar o ficheiro antes de executar;
        - A saída é mostrada depois de todo o código ser executado.

    ** Modo Interativo (Interative Mode)
        - O código é escrito e executado linha a linha;
        - Usado para testar pequenos pedaços de códgo;
        - Não é preciso salvar, o código é executado imediatamente;
        - A saída é mostrada imendiatamente após cada linha executada. 


# OPERADORES
- Quando comparamos (==) uma string com um número, o javascript automaticamente converte a string em um número. Isso se chama de "Implicit Conversion" ou "Implicit Type Casting" ou ainda "Type Coercion".

# CONTROL STRUCTURES IN PROGRAMMING

    ** Conditional Statements
        - if statement
        - if...else statement
        - if...else if...else statement
        - switch statement
        - ternary operator (condition ? true : false)
        - comparision operators (==, !=, ===, !==, >, >=, <, <=)


    ** Loops
        - for loop
        - while loop
        - do...while loop
        - for...of loop (arrays/iterables)
        - for...in loop (objects)
        - nested loops
        - loop control



# Conditional Statements

    ** IF Statement

    if (condition) {
        // code

        /*
            O if avalia condições lógicas complexas e faixas de valores (variáveis contínuas)
            Finalidade: Avalia expressões booleanas (verdadeiro ou falso).
            Uso ideal: Condições complexas com operadores (&&, ||, >, <) ou comparações de diferentes variáveis.
        */
    }

    - Verficar se tem idade para entrar na discoteca (if);
    - Verfificar se tem saldo suficiente para fazer uma transação no ecommerce (if...else);
    - verficar a taxa do transporte segundo a idade (if...else if...else)
        age < 12 - child ticket
        age < 65 - Adult ticket
        age >= 65 - senior ticket


    ** SWITCH Statement

    switch (condition) {
        // code

        /*
            O switch compara uma única variável contra valores exatos e constantes (variáveis discretas)

            Finalidade: Avalia correspondência exata de um único valor ou variável.
            Uso ideal: Listas longas de opções fixas, como escolher dias da semana, opções de menu ou níveis de acesso em um sistema.
        */
    }

    - Criar um sistema que verfica o nível de acesso de usuários em uma aplicação;
    - Criar um sistema que verifica os dias da semana e deixe uma mensagem usando (0 até 6)
        Domingo(0) - "Happy Weekend!"
        Segunda-feira(1) - "Happy Monday!"
        Terça-feira(2) - "Happy Midweek!"
        Quarta-feira(3) - "Happy Midweek!"
        Quinta-feira(4) - "Happy Midweek!"
        Sexta-feira(5) - "Thanks God It's Friday (TGIF)!"
        Sábado(6) - "Happy Weekend!";

    - Criar um sistema de opções de menu;


    ** TERNARY Statement
    ternary "condition ? true : false";


# Loops Statements

    ** Use cases of loops:

        - (Array Manipulation): Itarating Over Element Modifying Array Contents;
        - (DOM Traversal): Accessing DOM Nodes Updating DOM Elements;
        - (Event Handling): Handling Click Events Responding to Keyboard Input;
        - (Animation Control): Creating Animations Controlling Animation Frames;
        - (Data Processing): Processing User Input Transforming Data Sets

    ** Types of loops:

        - (for loop): Best when numbers of iterations is known;
        - (while loop): Best when numbers of iterations is unknown;
        - (do...while loop): Best when numbers of iterations is known;
        - (for...of loop): Best for user interation scenarios;
        - (for...in loop): Cleaner syntax for array iteration


    ** FOR Statement
        - Whatever should be repeating, I will put that statement inside the loop.
        - Track the number of times execution has happened.
        - Every single loop will have four components (initialization, condition, incrementation/decrementation and body).

    Order of execution: 
        1 - Initialization
        2 - Condition check
        3 - Body execution
        4 - Incrementation/Decrementation

    Ex: 

    let i;

    for (i = 1; i <= 5; i++) {
        console.log("*");
    }


    ** WHILE Statement

    let i = 1;

    while (i <= 5) {
        console.log("*");
        i++
    }


    ** DO...WHILE Statement

    let i = 1;

    do {
        console.log("*");
        i++
    } while (i <= 5);

QUESTION: When do I use for, while or do...while?
ANSWER: You have to solve N number of coding questions (at least 200 to 250), which builds your logical understanding, and hence will help you pick and choose the right loop in the right situation.


EXERCISES (Build Patterns)
    
    *****       *****       *                            
    *****       *   *       **          
    *****       *   *       ***         
    *****       *   *       ****        
    *****       *****       *****            