# 03while
03while

package exercicios;
//elaborar um programa que apresente no final o somatorio dos valores pares existentes na faixa de 1 ate 500.
public class Exercicio03while {

	public static void main(String[] args) {
		
		
		int contadora = 0;
		int soma=1;

		while (contadora <20) {
			if(contadora%2==1) {
				soma+=+contadora;
				//soma=soma+contadora;
				//as duas formas estão corretas 
			}
			contadora++;

		}
		System.out.println("A somatoria dos numeros pares entre 1 é 500 é :"+ soma);
	}
	}
