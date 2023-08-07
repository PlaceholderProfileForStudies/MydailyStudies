# Condições
1. **Como criar uma condição `if`:**  
    **Comando:**  
    ```java
        public static void main(String[] args) {
            int vida = 100;
            if(vida == 100){
                System.out.println("A vida está cheia!");
            }
	}
    ```
2. **Como criar uma condição `if-else`:**  
    **Comando:**  
    ```java
        public static void main(String[] args) {
            int vida = 99;
            if(vida == 100){
                System.out.println("A vida está cheia!");
            }else{
                System.out.printf("A vida está em %d%%",vida);
            }
	}
    ```
3. **Como criar uma condição `if-elif`:**  
    **Comando:**  
    ```java
        public static void main(String[] args) {
            int vida = 105;
            if(vida == 100){
                System.out.println("A vida está cheia!");
            }else if(vida > 100){
                vida = 100;
                System.out.println("A vida não pode estar a cima de 100%!");
            }else{
                System.out.printf("A vida está em %d%%",vida);
            }
	}
    ```