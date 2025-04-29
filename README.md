# Prime-Number
import java.util.Scanner;
public class PrimeNumber {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        boolean isPrime = false;
        for (int i = 2; i < n; i++) {
            if (n % i == 0) {
                isPrime = true;
                System.out.println("IS Prime");
                break;
            }
        }if(!isPrime){
                System.out.println("Not Prime");
            }
            }
        }
