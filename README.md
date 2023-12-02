import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Siapa namamu? ");
        String nama = scanner.nextLine();
        System.out.println("berapa umur kamu? ");
        int umur = scanner.nextInt();
        System.out.println("apa pekerjaan kamu? ");
        scanner.nextLine();
        String gawean = scanner.nextLine();
        
        
        
        System.out.println("Assalamualaikum " + nama);
        System.out.println("umurmu segini loh " + umur + "tahun ");
        System.out.println("gw kerjanya " + gawean);
    }
}
