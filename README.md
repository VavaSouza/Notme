# Notme
```java
import java.util.Scanner;

public class CalculadoraAreaTrapezio {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Digite o valor da base maior do trapézio: ");
        double baseMaior = scanner.nextDouble();
        
        System.out.print("Digite o valor da altura do trapézio: ");
        double altura = scanner.nextDouble();
        
        double area = ((baseMaior + baseMenor) * altura) / 2;
        
        System.out.println("Valores inseridos:");
        System.out.println("Base Maior: " + baseMaior);
        System.out.println("Altura: " + altura);
        System.out.println("A área do trapézio é: " + area);
    }
}
'''
