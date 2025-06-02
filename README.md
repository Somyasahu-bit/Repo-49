# Repo-49
Reverse number program
//Reverse number program
import java.util.Scanner;
class reverse{
    public static void main(String[] args) {
    int n,r;
    System.out.println("Enter any number");
    Scanner ref = new Scanner(System.in);
    n = ref.nextInt();
    
    while(n>0)
    {
        r=n%10;
        System.out.println(r);
        n=n/10;
    }
    }
     }
