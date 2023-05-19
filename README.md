# Programação Orientada a Objetos
## Tem o objetivo de aproximar o mundo real ao mundo digital.

### Vantagens da POO
* Confiável: O isolamento entre as partes gera um software seguro. Ao alterar uma parte, nenhuma outra é afetada.
* Oportuno: Como tudo é dividido em partes, elas podem ser desenvolvidas em paralelo.
* Manutenível: É mais fácil fazer uma atualização, pois uma pequena modificação beneficia todas as partes que utilizam o objeto.
* Extensível: O software não é estático, ele deve crescer para permancer útil.
* Reutilizável: Podemos utilizar os objetos de um sistema que criamos em outro sistema futuro.
* Natural: É mais fácil de entender, podemos nos preocupar mais na funcionalidade do que nos detalhes de implementação.

### Objeto
Coisa material ou abstrata que pode ser percebida pelos sentidos e descrita por meio de suas características

### Atributos
São as características

### Métodos/Funções
As "ações" que a classe pode executar.

### Instanciar uma classe
$variavel = new Classe();
Essa variável é um objeto.

Para usar um atributo dentro de uma função, é necessário o $this.
Não é seguro poder acessar os atributos fora da classe, por isso os declaramos como privados, assim só é possível acessá-los a partir dos Getters e Setters.

### Get - Pega o valor do atributo.
~~~
public function getEmail(){
  return->$this->email;
}
~~~

### Set - Altera o valor do atributo.
~~~
public function setEmail($e){
$this->email = $e;
}
~~~

### Construtor
É inicializado no momento em que a classe é instanciada.
~~~ 
public function __construct($nome){
  $this->setEmail = $email;
}
~~~

### Herança
Recurso que permite que classes compartilhem atributos e métodos ou comportamentos generalizados.


