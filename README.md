package one;
	public class Hello {
		protected void display(){
			System.out.println("I am able to access it from class Hello1");
		}
	}

	package two;

	import one.Hello;
	public class Hello1 extends Hello {
		public void displayit(){
			display();
		}
		}
package three;

	import two.Hello1;
	public class Main {
	    public static void main(String[] args) {
	    	Hello1 object1=new Hello1();
	    	object1.displayit();
	}
	}
	
 
 
 
 I am able to access it from class Hello1




