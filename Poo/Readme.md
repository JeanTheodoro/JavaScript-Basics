## Poo (Prpgramação orientado a Objetos) em _JavaScripts_

### Estrutura de uma Classe:
__Declaração__:

    Pessoa = function(){
        this.nome =  ''
        this.idade =  ''
        this.cpf = ''
        this.andar = function(){
            alert(this.nome)
        }
        thos.falar = function(){
            alert(this.telefone)
        }
    }

### Estrutura de um Objeto
__Declaração__:

    pessoa = new Pessoa()
    pessoa.nome = 'joão'
    pessoa.idade = '26'
    pessoa.cpf = '121211154'
    pessoa.andar()
    pessoa.falar()

## Estrutura mais rescente de declarar uma Classe:
__Declaração__ classe:
    class Retangulo{
        constructor(altura, largura) {
            this.altura = altura
            this.largura = largura
        }

        get calcularArea() {
            return this.altura * this.largura
        }    
    }


__Declaração__ objeto:

    const quadrado = new Retangulo(10,10) 
    alert("A Área de um retangulo com altura " + quadrado.altura + " cm  a largura " + quadrado.largura + " cm é de : " + quadrado.calcularArea )  