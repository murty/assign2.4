import java.util.Scanner;
class Days{
	public static void main(String args[])
{
		int n;
		int days;
		System.out.println("enter number of the month");
		Scanner in = new Scanner(System.in);
		n = in.nextInt();

switch (n){
case 1||3||5||7||8||10||12:
        days=31;
          break;
case 2:
	days=28;
          break;
case 4||6||9||11:
        days=30;
          break;
default:
	days=0;
}
System.out.println("days");
}
}
