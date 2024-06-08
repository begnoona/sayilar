import java.util.Scanner;



public class Main5 {

    public static void main(String[] args){
    

//Java döngüler ile 0'dan girilen sayıya kadar olan sayılardan 3 ve 4'e tam bölünen
// sayıların ortalamasını hesaplayan programı yazınız.

        int k;
        
Scanner input=new Scanner(System.in);

System.out.print("bir k sayisi giriniz: ");

k=input.nextInt();


for(int i=0;i<=k;i++)

{
    if(i%3==0 && i%4==0)
    
    {
    
        System.out.print(i +",");
    }
}
