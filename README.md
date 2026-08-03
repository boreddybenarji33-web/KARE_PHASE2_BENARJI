import java.util.*;
public class Main {
    public static void main(String []args) {
        Scanner obj=new Scanner(System.in);
        int n=obj.nextInt();
        int d,ed=0,od=0;
        while(n!=0) {
            d=n%10;
            if(d%2==0)
            ed++;
            else
            od++;
            n=n/10;
            System.out.println("odd digit count: "+od);
            System.out.println("even digit count: "+ed);
        }
    }
}
import java.util.*;
public class Main {
    public static void main(String[]args) {
        Scanner obj=new Scanner(System.in);
        int n = obj.nextInt();
        int c=0;
        while(n!=0)
        {
            n=n/10;
            c++;
            System.out.println("no of digits: "+c);
        }
    }
    
}
