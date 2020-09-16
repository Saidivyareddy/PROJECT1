import java.util.Scanner;
public class {
public static void main (String[] Strings){
double minutesInYear = 60 * 24 * 365;
Scanner input = new Scanner(System.in);
System.out.print("Input the number of minutes: ");
double min = input.nextdouble();
long years = (long) (min / minutesInYear);
Int days = (int) (min / 60 / 24) % 365;
System.out.println((int) min + " minutes is approximately "+ years +" years and"+ days+"days "
}
}
