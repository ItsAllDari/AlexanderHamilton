# AlexanderHamilton
import java.util.Scanner;

/**
 * Created by ItsAllDari on 5/29/17.
 */
public class AlexanderHamilton {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("How many pounds does Jack have? ");
       double pounds = input.nextDouble();

       System.out.print("How many shillings does Jack have? ");
       double shillings = input.nextDouble();

       System.out.print("How many pence does Jack have? ");
       double pence = input.nextDouble();

       System.out.print("Enter the pounds for the pie ");
       double PiePounds = input.nextDouble();

       System.out.print("Enter the shillings for the pie ");
       double PieShillings = input.nextDouble();

       System.out.print("Enter the pence for the pie ");
       double PiePence = input.nextDouble();

       System.out.print("Enter the pounds for the beer ");
       double BeerPounds = input.nextDouble();

       System.out.print("Enter the shillings for the beer ");
       double BeerShillings = input.nextDouble();

       System.out.print("Enter the pence for the beer ");
       double BeerPence = input.nextDouble();

       double amount = pounds + shillings + pence;

       int RemainingAmount = (int)(amount);

       int NumberOfPounds = RemainingAmount / 20;
       RemainingAmount = RemainingAmount % 20;

       int NumberOfShillings = RemainingAmount / 12;
       RemainingAmount = RemainingAmount % 12;

       int NumberOfPence = RemainingAmount;

       System.out.println("Jack's change is");
       System.out.println(NumberOfPounds + " pounds");
       System.out.println(NumberOfShillings + " shillings");
       System.out.println(NumberOfPence + " pence");



    }
}
