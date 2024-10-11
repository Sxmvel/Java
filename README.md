Trabalho prático - Programação orientada a objetos.

1° momento - desenvolvimento da matriz 3x3 ("Tabuleiro do racha-cuca").

package matriz;

public class Matriz {
   public static void main(String[] args) {
      int matriz [][] = new int [3][3];
      int soma = 1;        
        for(int i = 0; i < 3; i++){
            for(int j = 0; j < 3;j++){
                matriz[i][j] = soma++;
            }
        }
        for(int i = 0; i < 3; i++){
            for(int j = 0; j < 3;j++){
               System.out.print(matriz[i][j] +"");
        }
         System.out.println();
        }   
    }
 }
