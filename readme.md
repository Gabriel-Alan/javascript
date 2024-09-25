### JavaScript

- Linguagem criada por Brendan em 1995.
- EcmaScript versão padronizada do JS.
- Servidor onde armazena os arquivos e envia para o client.
- Client - Usuário que recebe o arquivo previamente enviado do servidor.

- Através do Node(ferramenta a ser baixada), podemos rodar e manusear o JS fora do navegador, ferramenta poderasa que utiliza o V8 engine.
- Podemos construir sites e plataformas através de HTML, CSS e JS. Construir Aplicativos Móveis com o framework ReactNative, entre muito mais possibilidades.

## Conceitos Básicos

- Variável é a forma de guardar um valor na memória, seja esse valor de qualquer tipo primitivo.

- No JavaScript podemos declarar variável de 3 formas
    - let = variável que pode ser alterada.
    - const = variável que não pode ser alterada.
    - var = forma padrão de declarar uma variável.

- alert(''): Cria um Pop-up com informações com apenas um botão 'OK'.
- Prompt(''): Cria um Pop-up com instrução e um espaço para coletar dados do client.

## Tipos Primitivos

Existem tipos primitivos de dados para ser usado em varáveis, algumas delas são:

    - String = Conjunto de caracteres que formam uma palavra,  frase ou texto
    - Number = é um conjunto de números.
    - Boolean = Tipo primitivo que interpreta 'true' ou 'false'
    - Undefined = valor não definido

Podemos usar o 'typeof var' para poder saber o tipo primitivo dos dados.

Para transformar a variável em outro tipo usamos 'Tipo(valor, var, etc)'

    Exemplo:
        Number("1") => 1

## Manipulando as Strings

var.length = Método para informar a quantidade de caracteres.
var.toUpperCase() = Método para deixar todas as letras maiúsculas.
var.toLowerCase() = Método para deixar todas as letras minúsculas.


Formatar na impressão de textos:
    - 'Qualquer texto ${Chamar variável}'. 
        ○ Exemplo: console.log('Qualquer texto ${Chamar variável}').

document.write('mensagem') = Comando para inserir uma mensagem no HTML no qual está associado ao JS.

Console.log('mensagem') = Comando para imprimir um texto no terminal.

## Operadores Aritméticos

Aritméticos
    (): Para priorizar uma conta
    **: exponenciação
    * / %: Multiplicação, divisão e resto da divisão por inteiro
    + - : Adição e Subtração

Auto atribuição
    Incrementando var += valor; 
    Decrementando var -= valor; 
    Incrementando um valor var++; 
    Decrementado um valor var--;
    
    - Forma de alterar o valor da própria variável na variável 
    
    - Raiz quadrada = qualquer número elevado a 0.5 
    
Relacionais
    > - Maior Que 
    < - Menor Que 
    >= - Maior Igual 
    <= - Menor Igual 
    == - Igual (Valor) 
    != - Diferente 
    === - Igual (Tipo) 

Lógicos 
    ! - Negação Diferente - (!=) 
    && - Conjunção (e) 
    || - Disjunção (ou) 
    
Ternário 
    ? :  
        ? - True 
        :  False 
        7 > 5? (caso verdadeiro executar):(caso falso executar) 

Precedência 
    1 = Relacionais 
    2 = ! 
    3 = && 
    4 = ||
