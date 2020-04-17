#incrementosDecrementos



public class cursoJava {

  public static void main(String args[]){
      
      int a= 3;
      int b= -a;
      
      System.out.println("b= " + b);
      
      boolean c = true;
      boolean d = !c;
      
      System.out.println("d= " + d );
      
//preincremento
      int e = 3;
      int f = ++e;
      System.out.println("f= " + f);
      System.out.println("e= "+ e );
      
//posincremneto
      int g= 5;
      int h= g++;
      System.out.println("g= "+g);
      System.out.println("h=" +h);
      
      //decremento
      //predecremento
      int i=3;
      int j=--i;
      System.out.println("i= "+i);
      System.out.println("j= "+j);
      
      //posdecremento
      int k=3;
      int l=k--;
      System.out.println("k= "+k);
      System.out.println("l= "+l);
    }

}
//******************************************************
public class ScannerConcatenacion {
    
    public static void main(String args[]){
        
        var scanner= new Scanner(System.in);
        
        System.out.println("Proporciona el nombre: ");
        String nombre =scanner.nextLine();
        
        System.out.println("Proporciona el id: ");
        var id = Integer.parseInt(scanner.nextLine());
        
        System.out.println("Proporciona el precio: ");
        double precio = Double.parseDouble(scanner.nextLine());
        
        System.out.println("Proporciona el simbolo: ");
        char simbolo = scanner.nextLine().charAt(0);
        
        System.out.println("Proporciona el envio gratuito: ");
        boolean envio= Boolean.parseBoolean(scanner.nextLine());
        
        System.out.println("\n\n");
        System.out.println(nombre +"#"+ id  );
        System.out.println("Precio:"+simbolo+precio);
        System.out.println("Envio gratuito:"+envio);
        
        
        
        
    }
}

//*****************************
public class Tarea03 {
    
    public static void main(String args[]){
        
        var scanner = new Scanner(System.in);
        
        System.out.println("Proporciona la altura del rectangulo:");
        int altura = Integer.parseInt(scanner.nextLine());

        System.out.println("Proporciona el ancho del rectangulo:");
        int ancho = Integer.parseInt(scanner.nextLine());

        int area = altura * ancho;

        int perimetro = (altura * ancho) * 2;

        System.out.println("\n\n");
        System.out.println("Area:" + area);
        System.out.println("Perimetro:" + perimetro);
    }
}

