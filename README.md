import java.util.Scanner;
public class fnamegoestolname
{
 public static void main (String [] arg){
 Scanner input = new Scanner (System.in);
 System.out.println ("Enter full name");
 String name = input.nextLine();
 int i = (name.indexOf(" "));
 System.out.print ("Hello " + (name.substring(i)));
 
}
}
