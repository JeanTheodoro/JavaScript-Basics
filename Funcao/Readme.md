## Funções em _JavaScripts_

As funções são ações executada, quando há uma ocorrência ou chamada de algum evento. As
funções podem receber parâmentros e retorna resultados, como por exemplo: operações matemáicas ou validação de de campos de formulário entre outras aplicações.

### Estrutura da Função:
__Declaração__:

    function sum(n1, n2){
        
        return n1 + n2
    }

    let sum = sum(1,2)


### Função Recursiva:
__Declarações__

    sum(0)    
    
    function sum (number){

        document.writeln(number)
        
        if(number >= 100){
            return 
        }

        sum(number + 1)
    }

    