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
