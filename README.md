# ussunu-alma
public class Main {
    public static void main(String[] args) {
        int n, k,total = 1;

        Scanner input = new Scanner(System.in);
        System.out.print( "üssü alınacak sayı : ");
        n = input.nextInt();
        System.out.print( "üs olacak sayı: ");
        k = input.nextInt();

        for (int i=1; i<=k; i++){
            total *=n;

        }
        System.out.print( "üslü sayı : " + total );




