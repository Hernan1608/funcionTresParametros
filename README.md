# funcionTresParametros
OpenBootCamp Ejercicio °1 parte 1.

public static void main(String[] args) {
    int num1 = 5;
    int num2 = 10;
    int num3 = 15;
    
    int resultado = sumaTresNumeros(num1, num2, num3);
    System.out.println("La suma de los tres números es: " + resultado);
}

En este ejemplo, se declaran tres variables num1, num2 y num3 y se les da un valor. Luego, se llama a la función sumaTresNumeros con estos tres valores como parámetros. El resultado se almacena en la variable resultado y se muestra en la consola usando System.out.println().

public static int sumaTresNumeros(int num1, int num2, int num3) {
    int resultado = num1 + num2 + num3;
    return resultado;
-------------------------------------------------------------------------------------------------------------------------------------------------------------
OpenBootCamp Ejercicio °1 parte 2

public class Coche {
    private int numPuertas;
    
    public Coche(int numPuertas) {
        this.numPuertas = numPuertas;
    }
    
    public int getNumPuertas() {
        return numPuertas;
    }
    
    public void addPuerta() {
        numPuertas++;
    }
    
    public static void main(String[] args) {
        Coche miCoche = new Coche(3);
        miCoche.addPuerta();
        System.out.println("Mi coche tiene " + miCoche.getNumPuertas() + " puertas.");
    }
}
