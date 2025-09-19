ublic class Main {
    public static void main(String[] args) {


        List<Integer> numeros = Arrays.asList(5, 10, 15, 20, 25, 30);


        int suma = 0;
        for (int num : numeros) {
            suma += num;
        }
        System.out.println("La suma de los números es: " + suma);


        List<String> nombres = new ArrayList<>();
        nombres.add("Jhon");
        nombres.add("Andrés");
        nombres.add("María");
        nombres.add("Camilo");
        nombres.add("Karent");

        System.out.println("\n--- Imprimiendo lista de nombres ---");


        System.out.println("Con FOR:");
        for (int i = 0; i < nombres.size(); i++) {
            System.out.println(nombres.get(i));
        }


        System.out.println("\nCon FOREACH:");
        for (String nombre : nombres) {
            System.out.println(nombre);
        }

        System.out.println("\nCon WHILE:");
        int i = 0;
        while (i < nombres.size()) {
            System.out.println(nombres.get(i));
            i++;
        }
    }
}
