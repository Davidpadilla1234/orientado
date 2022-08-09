
    package javaapplication6;
    import java.util.Scanner;

    public class JavaApplication6 {
        public static void main(String[] args) {
            Scanner  as=new Scanner (System.in);
            System.out.println("tamaño de la lista?");
            int bg=as.nextInt();
            int lista[]=new int[bg];
            for (int g=0;g<bg;g++){
                System.out.println("valores:");
                int x=as.nextInt();  
                lista[g]=x;
                }
            for (int xx=0;xx<bg;xx++)
                {
                System.out.println("lista:"+ lista[xx]);
                }
        }
    }
