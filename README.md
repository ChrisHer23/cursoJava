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

//tarea 05 procedencia de operadores 
public class Tarea05 {
    
    public static void main(String args[]){
        
        int a = 2;
        int b = 3;
         
        int res = -3 + 6/ ++a * 4 - b-- + b; 
        //incrementa a++ =2+1=3
        //-3+(6/3))*4-3+3
        System.out.println("1er operacion realizada(6/3):" +(6/3)); //vale 2
        //-3+(2)*4-3+3
        System.out.println("2da operacion realizada(2*4): " + (2*4)); //vale 8
        //-3+(8)-3+3
        System.out.println("3er operacion realizada(-3+8): "+(-3+8));//vale 5
        //(-3+8)-3+3
        //5-3+(--3)
        
        System.out.println("4ta operacion realizada(5-3): " +(5-3)); //vale 2
        //2+2 
        System.out.println("ultima operacion realizada(2+2): "+(2+2));//vale 4
       
        System.out.println("El resultado es: "+res);
        
    }
    
}
//**************condicion if else -else if 
 var condicion = true;

        if (condicion) {

            System.out.println("condicion verdadera");
        } else {
            System.out.println("condicion falsa");
        }
        var numero = 2;

        if (numero == 1) {

            System.out.println("el numero es 1");

        } 
        else if (numero == 2){
            System.out.println("el numero es 2");
        }
        
        else if(numero == 3){
            System.out.println("el numero es 3");
            
        }
        else {
            System.out.println("valor desconocido ");
        }

    }
//***************switch 
 var calificacion = new Scanner(System.in);
        System.out.println("Ingresa tu calificacion entre 0 y 10");
        int calif2 = Integer.parseInt(calificacion.nextLine());

        if (calif2 >= 0 && calif2 <= 5) {

            System.out.println("Tu nota es F");
        } else {

            //int calif2 =3;
            String calNota;

            switch (calif2) {

                case 6:
                    calNota = "Tu nota es D";
                    break;

                case 7:
                    calNota = "Tu nota es C";
                    break;

                case 8:
                    calNota = "Tu nota es B";
                    break;

                case 9:
                    calNota = "Tu nota es A";
                    break;

                case 10:
                    calNota = "Tu nota es A";
                    break;

                default:
                    calNota = "nota desconocida";

            }

            System.out.println(calNota);
        }
}
