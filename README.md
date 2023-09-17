# tarea_xpc
Primer tarea de Fundamentos de Programacion



// INICIO
import java.util.Scanner;
public class tarea_xpc {
       public static void main(String[] args){

/// Calcular el área de un circulo    
    {
        try (Scanner sc = new Scanner(System.in)) {
            System.out.println("ingrese el radio del circulo");
            double radio = sc.nextDouble();

            double area = radio * radio * 3.1416;

            System.out.println("El área del circulo es: " + area);
        }
    }
    

// Verificar si un número es par o impar.
      {  int numero = 8; {
        if (numero % 2 == 0){
            System.out.println("El numero" + numero + " es par.");
        } else {
            System.out.println("El número" + numero + " es impar.");
        }
            }
}
    
// Verificar si un año es bisiesto o no

       { 
        int anio = 2024;{
        
        if ((anio % 4 == 0) && ((anio % 100 != 0) ) || (anio % 400 == 0)) {
        System.out.println("El año" + anio + " es bisiesto.");
        } else {
            System.out.print("El año " + anio + " no es bisiesto.");
             }
            }
}

// Calcular la suma de los dígitos de un número.

{
    int[] digito = { 1, 2, 3, 4 };
    int suma = digito [0] + digito [1] + digito [3];
    System.out.println("la suma de los digitos del numero es: " + suma);
}
   // FIN
    }
}
