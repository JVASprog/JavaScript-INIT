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