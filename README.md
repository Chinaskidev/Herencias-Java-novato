public class Main {
    public static void main(String[] args) {
        Cliente cliente = new Cliente();
        cliente.edad = 30;
        cliente.nombre = "Juan";
        cliente.telefono = 23456;
        cliente.credito = 2;
        System.out.println("Nombre: "+cliente.nombre);
        System.out.println("Edad: "+cliente.edad);
        System.out.println("Telefono: "+cliente.telefono);
        System.out.println("Credito: "+cliente.credito);

        Trabajador trabajador = new Trabajador();
        trabajador.Salario = 2500;
        System.out.println("Salario:"+trabajador.Salario);

    }

}
class Persona{
    int edad;
     String nombre;
     long telefono;

}

class Cliente extends Persona{
     int credito;

}
class Trabajador extends Persona{
    int Salario;

}


