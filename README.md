# MethodTutorial

////////////////////////////////////////////////////////////////////////////////////////
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner=new Scanner(System.in);
        System.out.println("Plese insert your name");
        String name=scanner.next();

        System.out.println("Hello world!");
        System.out.println("Please insert your saving amount");
        int SavingAmount=scanner.nextInt();
        additon(4,5);
        subtraction(4.5,6);
        multiplication(7,9);
        System.out.println(myofthestudent());
        greeting(name);
        loanamount(SavingAmount);
    }
    static void additon(int num1,int num2)
    {
        int sum=num1+num2;
        System.out.println(sum);
    }
    static void subtraction(double num3,int num4)
    {
        double sub=num3-num4;
        System.out.println(sub);

    }
    static void multiplication(int num5,int num6)
    {
        int mul=num5*num6;
        System.out.println(mul);
    }
    static String myofthestudent()
    {
        System.out.println("Marta Abebe");
        return"Marta Abebe W.";
    }
    static void greeting(String username){
        System.out.println("Hi"+username);
    }
    static void loanamount(int SavingAmount){
       // return SavingAmount*4;
        if(SavingAmount>20000)

            System.out.println(" you can borow"+SavingAmount*4);
            else
            System.out.println("you are not eligible for loan");
        }
    }


