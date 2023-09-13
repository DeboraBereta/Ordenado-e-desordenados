# Ordenado-e-desordenados em JAVA
Ordena números aleatórios inseridos pelo usuário na linguagem java

import java.util.Arrays;
import java.util.Scanner;

public class atv1 {
    public static void main(String[] args) {
        
        Scanner ler = new Scanner(System.in);

        int[] nmr = new int [10];
       

        //ler 10 numeros aleatorios digitado pelo usuario
        for (int i = 0; i < 10; i++) {

            System.out.println("Digite o "+ (i+1)+ "° número: ");
            // recebe numero de entrada.
            nmr[i] = ler.nextInt();
            
        }
        //exibe as informacoes.
        System.out.println("Ordem original: " + Arrays.toString(nmr));
        Arrays.sort(nmr);
        System.out.println("Ordem crescente: " + Arrays.toString(nmr));


       
    }

}
