# POO Example

## O que é POO? 
<p> Programação orientada a objetos (POO) é um paradigma de programação baseado no conceito de "objetos", que podem conter dados na forma de campos, também conhecidos como atributos, e códigos, na forma de procedimentos, também conhecidos como métodos. 
</p>
<p> A POO é constituida de pilares que são requerimentos, sendo esses: Abstração,Encapsulamento,Herança,Polimorfismo os quais serão listados abaixo.
</p>
 
## Abstração
<p> A abstração é o ponto de partida para a criação de programas utilizando POO. Trata-se da capacidade de extrair dos personagens ou dos itens presentes no contexto, suas principais características, criando, dessa forma, objetos. </p>

## Encapsulamento 
<p>Incluir ou proteger alguma coisa em uma cápsula, Encapsular os dados de uma aplicação significa evitar que estes sofram acessos indevidos. Para isso, é criada uma estrutura que contém métodos que podem ser utilizados por qualquer outra classe, sem causar inconsistências no desenvolvimento de um código. </p>

## Herança
<p>Herança é um princípio de orientação a objetos, que permite que classes compartilhem atributos e métodos, através de "heranças". Ela é usada na intenção de reaproveitar código ou comportamento generalizado ou especializar operações ou atributos.</p>

## Polimorfismo 
<p>Polimorfismo é o princípio pelo qual duas ou mais classes derivadas da mesma superclasse podem invocar métodos que têm a mesma assinatura, mas comportamentos distintos.</p>

# Como esse código aplica esse conceitos? 
<small>Poo na prática</small>
<p> Nesse código é possivel a criação dos objetos Bottle e Cupoftea, ambos possuem uma capacidade, peso e um valor atual de liquido tais atributos foram herdados da classe mãe Containers, entretaneto os objetos possuem características próprias pelas quais existem métodos de acesso distintos.     
</p> 
<p> É possivel criar um novo objetos atribuindo diferente peso e capacidade de acordo e configurando isso após a criação, você é convidado para criar um objeto que será incrementado ao menu. 
</p>
<p>Métodos herdados: preencher,esvaziar,calcular peso.</p>

<center><b>Exemplo de objeto, uma garrafa: </b></center> 

``` 
package com.company.felipe;
public class Bottle extends Containers {
    private int capacityMax;
    private double weight;
    private int currentValueMl;
    private boolean thermal;
    public Bottle() {
        this.capacityMax = capacityMax;
        this.weight = weight;
        this.currentValueMl = currentValueMl;
    }
    public boolean isThermal() {
        return thermal;
    }
    public void setThermal(boolean thermal) {
        this.thermal = thermal;
    }
}

```
---

⭐️ From [DarlanNoetzold](https://github.com/DarlanNoetzold)
