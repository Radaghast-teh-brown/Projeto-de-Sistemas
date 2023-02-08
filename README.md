# Projeto-de-Sistemas
Notas sobre a disciplina de Projeto de Sistemas - Java

## - Coisas diversas
Camel case -> getNome, criarConta

Snake case -> get_nome, criar_conta

##  Visibilidade entre classes

A palavra reservada private restringe a visibilidade dos métodos e dos atributos de uma classe. Quando uma classe utiliza atributos e métodos públicos devemos acrescentar a palavra public. Como exemplo temos a classe abaixo


```
public class Aluno {
  private String nome;
  private int idade;
  
  public Aluno(String pNome, int pIdade){
    nome = pNoME
    idade = pIdade
  }
  
 public void getAluno(){
    System.out.println("Meu nome é" + this.nome + " e minha idade é" + this.idade);
 }
}

```
 ## Encapsulamento 
 
 Quando não queremos permitir o acesso direto aos atributos e métodos de uma classe podemos encapsulá-la para que estas informações sejam disponíveis em apenas algumas situações. Na imagem abaixo podemos ver que o se os atributos forem privados não temos acesso direto a eles.
 
 ![image](https://user-images.githubusercontent.com/84158231/217602983-fb7928d2-8f7a-47dd-b1f8-33f6416fc1a2.png)

## Herança

## Polimorfismo
