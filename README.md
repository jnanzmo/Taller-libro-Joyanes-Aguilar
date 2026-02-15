public class Main {
    public static void main(String[] args) {
        double base = 5;
        double altura = 3;
        System.out.println((base * altura) / 2);
    }
}




public class Main {
    public static void main(String[] args) {
        double r = 5; // radio de ejemplo
        double longitud = 2 * Math.PI * r;
        double area = Math.PI * r * r;

        System.out.println(longitud);
        System.out.println(area);
    }
}



public class Main {
    public static void main(String[] args) {
        double tarifaHoraria = 10;
        double horasDiarias = 8;
        int diasSemana = 7;

        double salarioSemanal = tarifaHoraria * horasDiarias * diasSemana;
        System.out.println("El salario semanal es: " + salarioSemanal);
    }
}




public class Main {
    public static void main(String[] args) {
        int A = 2;
        int B = 5;

        double resultado = 3 * A - (4.0 * B) / (A * A);

        System.out.println("El resultado es: " + resultado);
    }
}




public class Main {
    public static void main(String[] args) {

        double P1 = 4.0 / 2 * 3 / 6;
        double P2 = 6.0 / 2 / 1 / Math.pow(5, 2) / 4 * 2;

        double resultado = P1 + P2;

        System.out.println("El resultado es: " + resultado);
    }
}










public class Main {
    public static void main(String[] args) {
        // Valores de ejemplo (puedes cambiarlos)
        double a = 1, b = 3, c = 2, d = 1;
        double x = 2, y = 4, z = 5, r = 3;
        double x1 = 1, y1 = 2, x2 = 4, y2 = 6;
        double expr_a = Math.sqrt(b*b - 4*a*c);
        double expr_b = (x*x + y*y) / (z*z);
        double expr_c = (3*x + 2*y) / (2.0*z);
        double expr_d = (a + b) / (c - d);
        double expr_e = 4*x*x - 2*x + 7;
        double expr_f = (x + y) / x - (3.0*x) / 5.0;
        double expr_g = a / (b * c);
        double expr_h = x * y * z;
        double expr_i = (y2 - y1) / (x2 - x1);
        double expr_j = 2 * Math.PI * r;
        double expr_k = (4.0/3.0) * Math.PI * r * r * r;
        double expr_extra = Math.pow(x2 - x1, 2) + Math.pow(y2 - y1, 2);   


        System.out.println("a) " + expr_a);
        System.out.println("b) " + expr_b);
        System.out.println("c) " + expr_c);
        System.out.println("d) " + expr_d);
        System.out.println("e) " + expr_e);
        System.out.println("f) " + expr_f);
        System.out.println("g) " + expr_g);
        System.out.println("h) " + expr_h);
        System.out.println("i) " + expr_i);
        System.out.println("j) " + expr_j);
        System.out.println("k) " + expr_k);
        System.out.println("extra) " + expr_extra);
    }
}







