package sample.model;

public class Produto {
   //atributos
   private String nome;
   private double preco;

   //métodos
   public String getNome() {
       return nome;
   }

   public void setNome(String nome) {
       this.nome = nome;
   }

   public double getPreco() {
       return preco;
   }

   public void setPreco(double preco) {
       this.preco = preco;
   }

   @Override
   public String toString() {
       return "Produto{" +
               "nome='" + nome + '\'' +
               ", preco=" + preco +
               '}';
   }
}












package sample;

import sample.model.Produto;

public class Main {

   public static void main(String[] args) {

       Produto produto = new Produto();
       Produto.setNome("Laranja");
       Produto.setPreco(“3,50”);

       System.out.println(Produto);

   }
}
































Atividade Cliente

package sample.model;

public class Cliente {
   //atributos
   private String nome;
   private String email;
   private String telefone;
   private int idade;
  
   //get and set

   public String getNome() {
       return nome;
   }

   public void setNome(String nome) {
       this.nome = nome;
   }

   public String getEmail() {
       return email;
   }

   public void setEmail(String email) {
       this.email = email;
   }

   public String getTelefone() {
       return telefone;
   }

   public void setTelefone(String telefone) {
       this.telefone = telefone;
   }

   public int getIdade() {
       return idade;
   }

   public void setIdade(int idade) {
       this.idade = idade;
   }

   @Override
   public String toString() {
       return "Cliente{" +
               "nome='" + nome + '\'' +
               ", email='" + email + '\'' +
               ", telefone='" + telefone + '\'' +
               ", idade=" + idade +
               '}';
   }
}



package sample;

import sample.model.Cliente;

public class Main {

   public static void main(String[] args) {

       Cliente cliente = new Cliente();
       Cliente.setNome("João");
       Cliente.setEmail("joão@estudante.do.senai.br");
       Cliente.setTelefone("48999999999");
       Cliente.setIdade(17);

       System.out.println(Cliente);

   }
