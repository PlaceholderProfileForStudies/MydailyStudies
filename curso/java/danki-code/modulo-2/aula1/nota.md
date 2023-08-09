# Programa de leitura
1. **Como fazer o programa ler algo digitado no teclado:**  
    **Comando:**  
```java
    import java.util.Scanner;
    public static void main(String args[]) {
            Scanner in = new Scanner(System.in);
            System.out.print("Digite o seu nome: ");
            String nome = in.nextLine();
            System.out.printf("Seja bem vindo(a) %s!",nome);
	}
```