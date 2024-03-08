import java.util.Scanner;
public class teste {

    public static void main(String []args)
    {
    Scanner teclado = new Scanner (System.in);

    int valor1;
    int valor2;
    int soma;


    System.out.println("Digite o valor 1");
     valor1= teclado.nextInt();

    System.out.println("Digite o valor 2");
     valor2= teclado.nextInt();

     soma = valor1+valor2;

    System.out.println("a soma da:"+soma);
   
    }
 

}
