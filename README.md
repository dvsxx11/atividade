package atividade;

public class LOJAREFATORADA {

	public static void main(String[] args) {
		
		Preco("Celular", 2000.0, 0.10);
        Preco("Notebook", 4500.0, 0.15);
        Preco("Tablet", 1500.0, 0.05);
    }

    public static void Preco(String nome, double preco, double descontoPercentual) {
        double desconto = preco * descontoPercentual;
        double Final = preco - desconto;
        
     System.out.println(nome + " = Preço final: R$ " + Final);
   }
}
		


//3.
// R: Usando métodos reutilizáveis, o código ficou bem menor, mais legível, mais limpo, tornou-se mais fácil de entender e facilitou futuras modificações.
