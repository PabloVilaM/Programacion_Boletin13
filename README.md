

2- Que visualizas no seguinte programa :

class Ejercicio { 
 public static void main (String [] args) { 
 Clase1 obj1= new Clase1(5,4); 
 System.out.print(obj1.modificar(4)+" ");  === 9
 Clase1 obj2= new Clase1(5,4); 
 System.out.print(obj2.modificar(5)+" "); === 10
 obj2=obj1; 
 System.out.println(obj2.modificar(5)+" "); === 14
 }//fin main 
} 
class Clase1{ 
 int p1,p2; 
 public Clase1 (int i, int j){ 
 p1=i; 
 p2=j; 
 } 
 public int modificar(int i){ 
 p1=p1+i; 
 p2=p2+i; 
 System.out.print(p2+" "); === 8 + “” , 9 +”” , 13 “”	
 return p1; 
 }
