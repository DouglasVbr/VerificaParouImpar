# VerificaParouImpar



package verificaparouimpar;

import java.util.Scanner;

public class VerificaParouImpar {

    
    public static void main(String[] args) {
        
        Scanner Scanner = new Scanner(System.in);
        // solicita ao usuario que insira um número  
        
        System.out.println("Digite um número inteiro");
        int numero = Scanner.nextInt();
        
        // verifica se o número é par ou impar
        
        if(numero%2==0){
            System.out.println("o número é par");
        }else{
            System.out.println("o número é impar");
            
        }
        //fecha o scanner
        
        Scanner.close();
    }
    
}
