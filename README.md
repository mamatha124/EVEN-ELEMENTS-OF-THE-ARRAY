# EVEN-ELEMENTS-OF-THE-ARRAY 
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        int a[];
        a=new int[100];
        Scanner sc= new Scanner(System.in);
        int n=sc.nextInt();// Array length
        for(int i=0;i<n;i++){
            int k=sc.nextInt();
            a[i]=k;
        }
        for(int i=0;i<n;i++){
            if (a[i]%2==0)
            System.out.print(a[i]+" ");
        }
    }
}
