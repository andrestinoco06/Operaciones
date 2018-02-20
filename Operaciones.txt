import java.util.Scanner;

public class Operaciones {
    public static void main(String[] args) {
        int num1, num2;
        int resultado;
        Scanner S = new Scanner (System.in);
        System.out.println("Introduce el primer valor: ");
        num1 = S.nextInt();
        System.out.println("Introduce el segundo valor: ");
        num2 = S.nextInt();
        resultado = num1+num2;
        System.out.println("El resultado de la suma es: "+resultado);
        resultado = num1-num2;
        System.out.println("El resultado de la resta es: "+resultado);
        resultado = num1*num2;
        System.out.println("El resultado de la multiplicacion es: "+resultado);
        resultado = num1/num2;
        System.out.println("El resultado de la division es: "+resultado);
        resultado = num1%num2;
        System.out.println("El resultado del modulo es: "+resultado);
    }
}