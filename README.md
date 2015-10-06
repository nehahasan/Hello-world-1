# Hello-world
I LOVE :coffee:and:pizza:.

import java.util.*;  
  
class Main{  
 private static Scanner in;

public static void main(String[] args){
	 
	 Random random = new Random();  
	 int captcha = random.nextInt(5000);
	 System.out.print(captcha);
	 
  
      in = new Scanner(System.in);
      
      System.out.println("\nEnter the above captcha: ");
      String input = in.nextLine();
  
      if(!input.equals(captcha))
    	  System.out.println("Captcha matched");
      else
    	  System.out.println("Captcha not matched... ");
  
 }  
}  
