# Projeto-de-Sistemas
Notas sobre a disciplina de Projeto de Sistemas - Java

## - Coisas diversas
Camel case -> getNome, criarConta

Snake case -> get_nome, criar_conta

## -1 Visibilidade entre classes

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
 
