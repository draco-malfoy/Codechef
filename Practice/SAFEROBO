import java.util.Scanner;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
    public static void main (String[] args) throws java.lang.Exception
    {
        Scanner sc = new Scanner(System.in);
        try{int cases = sc.nextInt();
        
        outer:
        for(int i = 0; i < cases; i++) {
            String cells = sc.next();
            int sA = sc.nextInt();
            int sB = sc.nextInt();
            int hA = 0;
            int hB = cells.length() - 1;
            while(hA <cells.length()-1 && hB>=0) {
                hA = hA + sA;
                hB = hB - sB;
                if(hA == hB) {
                    System.out.println("unsafe");
                    continue outer;
                }
            }
            System.out.println("safe");
        }
        sc.close();
        }catch(Exception e){
            
        }
    }
}
