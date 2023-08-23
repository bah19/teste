
import java.util.Scanner;

public class Main{
  public static void main(String[] args){
    Scanner sc = new Scanner(System.in);
    int a, b, soma, multiplicacao, divisao, raio1, quadrado1, raio2, quadrado2;
    a=sc.nextInt();
    b=sc.nextInt();
    soma=a+b; multiplicacao=a*b; divisao=a/b; raio1=a/2; raio2=b/2; quadrado1=a*2; quadrado2=b*2;
    System.out.print("A soma deu: "+soma); System.out.print("A multiplicacao deu: "+multiplicacao); System.out.print("A divisao deu: "+ divisao);
    System.out.print("O raio de "+a+" deu: "+raio1); System.out.print("O raio de "+b+" deu: "+raio2); System.out.print("O quadrado de "+a+"deu: "+quadrado1);
    System.out.print("O quadrado de "+b+"deu: "+quadrado2);
    sc.close();
}}
