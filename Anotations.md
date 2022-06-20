# Anotações JavaScript

## CONST e VAR

    var -> declara variaveis, q podem ser alterados ao longo do codigo(dinamica)
    cost -> declara uma constante estatica que n pode ser alterada ao longo do codigo(estatica)

## FUNCAO

    function(){   -> declara uma funcao que recebe parametros em () e retorna um valor com 'return'.
        return ... ;  -> caso so precise manipular, nao precisamos do return.
    }

    

## CONSOLE

    console.log() -> serve mais para debug, faz com que o valor apareça no console.

### BROWSER     

    var heading1 = document.getElementsByTagName()[] -> serve para selecionar e especionar um elemento da pagina web, selecionando atraves do tipo de TAG (h1, h2, entre outras tags) e o índice do vetor dentro dos []. Colocando essa informação na variavel heading1, eu posso mexer nela, seja usando o CSS, pelo console.

    exemplo, mudando a cor do h1 pra vermelho:

    heading.style.color = 'red'

## IMPORTANDO PARA O HTML

    importando arquivo .css
    <link rel="stylesheet" href="caminho do arquivo css">

    importando arquivo JS -> se o script for muito grande, recomendado colocar antes da tag fechamento html.
    <script src="caminho do arquivo JS"></script>

## MANIPULANDO ARRAYS

    forEach() -> executa uma funcao para cada indice do array
    push() -> adiciona um item ao final do array
    pop() -> remove o ultimo item do array
    shift() -> remove o primeiro item do array
    unshift() -> adiciona um item ao inicio do array
    indexOf() -> retorna o indice de um valor do array
    splice() -> remove ou substitui um item pelo indice
    slice() -> retorna uma parte de um array existente


    como chamar as funcoes: array.funcao(item, index) -> array é o nome do array criado e a função é uma dessas citadas acima.
    ou array.funcao(qualquer coisa)

## Objetos
    
    Variável que possui varias propriedades, separadas por ','
    exemplo de objeto: de uma xicara pequena azul

    var xicara = {
        cor: 'azul;,
        tamanho: 'p',
        funcao: tomarCafe()
    }

    desestruturando:
    podemos atribuir as propriedades à variáveis para trabalhar com elas.

    var cor = xicara.cor;
    var tamanho = xicara.tamanho;
    var funcao = tomarCafe();

    podemos utilizar chaves também:

    var {cor, tamanho, funcao} = xicara;

## SWITCH

    Funciona da mesma forma que em C.

    switch(variavel){
        case variavel = condicao1:
            funcao para esse caso;
            break;

        case variavel = condicao2:
            funcao para esse caso;
            break;

        default:
            funcao para nenhum caso acima;
            break;  
    }

## FUNCOES

    prompt -> forma de pegar alguma informacao escrita pelo usuario atraves de um alert box.

    let n1 = Number(prompt('insira um valor:')); 
    o Number, força a string que é entrada pelo usuário a se tornar um tipo 'number'.

    alert -> abre um popup
    templateStrings -> aberta com crases, possibilita utilizar strings junto com expressoes.

    exemplo:

    function soma(){
        resultado = n1 + n2;
        alert(`${n1} + ${n2} = ${resultado}`);
    }

    

