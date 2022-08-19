# Programação Orientada a Objetos

## Aplicação e conceitos em C#

------------



#### Herança
Classe A(SubClasse) "É um" classe B(SuperClasse). 
Permite Subclasses(especialização) estendam os atributos e metodos de uma superclasse(generalização).
		  

------------


#### Polimorfismo  
Classes derivadas de uma única classe base são capazes de invocar os métodos que, embora apresentem a mesma assinatura, 
comportam-se de maneira diferente para cada uma das classes derivadas.
Mecanismo por meio do qual selecionamos as funcionalidades utilizadas de forma dinâmica por um programa no decorrer de sua execução.
Os mesmos atributos e objetos podem ser utilizados em objetos distintos, porém, com implementações lógicas diferentes. 

------------


#### Abstração 
Abstrair do mundo real conceitos mais relevantes e genéricos que podem ser especializados por outras classes.
Ela define um modelo (template) para uma funcionalidade e fornece uma implementação incompleta -
a parte genérica dessa funcionalidade - que é compartilhada por um grupo de classes derivadas. 
Cada uma das classes derivadas, completa a funcionalidade da classe abstrata adicionando um comportamento específico. 

------------


#### Encapsulamento 
É a técnica que faz com que detalhes internos do funcionamento de um software permaneçam ocultos.
private(default), public, internal, protect, protect internal e private protect, sealed(only class). 
				 

------------


#### Composição  
Classe A "Tem um" classe B.
Permite que uma classe compartilhe seus atributos e metodos a uma outra classe. 

------------


#### ALTA COESÃO BAIXO ACOPLAMENTO

###### Acoplamento 
Uma dependencia direta entre um objeto e outro. Quando um objeto muda o outro muda por consequencia.

###### Coesão 	 
Responsabilidade única, uma classe deve ter apenas uma única responsabilidade e realizá-la de maneira satisfatória, ou seja, uma classe não deve assumir responsabilidades que não são suas .

------------


