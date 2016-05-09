# exercicio-01-1-bimestre

// 01.faça um programa que peça 2 numeros e imprima o maior deles.
import java.util.Scanner;

public class Exercicio01 {

	public static void main(String[] args) {
		Scanner teclado = new Scanner (System.in);
		System.out.println("Informe dois números:");
		int numero1 = teclado.nextInt();
		int numero2 = teclado.nextInt();
		if (numero1 > numero2){
			System.out.println("o primeiro numero é maior que o segundo!");
		}else if(numero2 > numero1){
			System.out.println("o segundo numero é maior que o primeiro!");
		}
		
	}

}
