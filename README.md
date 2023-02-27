# EjerciciosLogica 1
import java.util.Scanner;
 
public class Pitagoras
{
    public static void main(String args[])
    {
        float cateto1, cateto2, hipotenusa;
 
        Scanner s = new Scanner(System.in);
        System.out.print("Ingresa el valor de los dos catetos: ");
        cateto1 = s.nextFloat();
        cateto2 = s.nextFloat();
 
        hipotenusa = (float) Math.sqrt(Math.pow(cateto1, 2) + Math.pow(cateto2, 2));
 
        System.out.println("La hipotenusa es: " + hipotenusa);
    }
}
# Ejercicio Logica 2
import java.util.Scanner;
 
public class ParImpar
{
    public static void main(String args[])
    {
        int numero;
 
        Scanner s = new Scanner(System.in);
        System.out.print("Ingresa un número: ");
        numero = s.nextInt();
 
        if (numero % 2 == 0)
            System.out.println(numero + " es un número par.");
        else
            System.out.println(numero + " es un número impar.");
    }
}
Ejercicio logica 3
import java.util.Scanner;
 
public class AngulosTriangulo
{
    public static void main(String args[])
    {
        float angulo1, angulo2, angulo3;
 
        Scanner s = new Scanner(System.in);
        System.out.print("Ingresa el valor de los dos ángulos: ");
        angulo1 = s.nextFloat();
        angulo2 = s.nextFloat();
 
        if ((angulo1 > 0 && angulo1 < 180) && (angulo2 > 0 && angulo2 < 180))
        {
            angulo3 = 180 - (angulo1 + angulo2);
            System.out.println("El tercer ángulo es: " + angulo3);
        }
        else
            System.out.println("Los valores ingresados no son válidos.");
   
   Ejercicio logica 4
   import java.util.Scanner;
 
public class Promedio
{
    public static void main(String args[])
    {
        float num1, num2, num3, promedio;
 
        Scanner s = new Scanner(System.in);
        System.out.print("Ingresa los tres números: ");
        num1 = s.nextFloat();
        num2 = s.nextFloat();
        num3 = s.nextFloat();
 
        promedio = (num1 + num2 + num3) / 3;
 
        System.out.println("El promedio es: " + promedio);
    }
    
    #Ejercicio logica 5
    import java.util.Scanner;
 
public class LongitudCadena
{
    public static void main(String args[])
    {
        String cadena;
        int longitud;
 
        Scanner s = new Scanner(System.in);
        System.out.print("Ingresa una cadena de texto: ");
        cadena = s.nextLine();
 
        longitud = cadena.length();
 
        System.out.println("La longitud de la cadena es: " + longitud);
    }
}

#Ejercicio logica 6
import java.util.Scanner;
 
public class AreaTriangulo
{
    public static void main(String args[])
    {
        float base, altura, area;
 
        Scanner s = new Scanner(System.in);
        System.out.print("Ingresa la base y la altura del triángulo: ");
        base = s.nextFloat();
        altura = s.nextFloat();
 
        area = (base * altura) / 2;
 
        System.out.println("El área del triángulo es: " + area);
    }
}
#Ejercicio logica 7
import java.util.Scanner;
 
public class RaizCuadrada
{
    public static void main(String args[])
    {
        int numero;
        double raizCuadrada;
 
        Scanner s = new Scanner(System.in);
        System.out.print("Ingresa un número: ");
        numero = s.nextInt();
 
        raizCuadrada = Math.sqrt(numero);
 
        System.out.println("La raíz cuadrada es: " + raizCuadrada);
    }
}

#Ejercicio Logica 8
import java.util.Scanner;
 
public class MCD
{
    public static void main(String args[])
    {
        int A, B, resto;
 
        Scanner s = new Scanner(System.in);
        System.out.print("Ingresa los dos números: ");
        A = s.nextInt();
        B = s.nextInt();
 
        while (B != 0)
        {
            resto = A % B;
            A = B;
            B = resto;
        }
 
        System.out.println("El MCD es: " + A);
    }
}

#Ejercicio Logica 9
import java.util.Scanner;
 
public class CadenaInversa
{
    public static void main(String args[])
    {
        String cadena;
 
        Scanner s = new Scanner(System.in);
        System.out.print("Ingresa una cadena de texto: ");
        cadena = s.nextLine();
 
        for (int i = cadena.length() - 1; i >= 0; i--)
            System.out.print(cadena.charAt(i));
 
        System.out.println();
    }
}

#Ejercicio logica 10
import java.util.Scanner;
 
public class AreaRectangulo
{
    public static void main(String args[])
    {
        float base, altura, area;
 
        Scanner s = new Scanner(System.in);
        System.out.print("Ingresa la base y la altura del rectángulo: ");
        base = s.nextFloat();
        altura = s.nextFloat();
 
        area = base * altura;
 
        System.out.println("El área del rectángulo es: " + area);
    }
}
