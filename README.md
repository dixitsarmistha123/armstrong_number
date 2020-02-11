# armstrong_number
check whether the number is an Armstrong number or not.
import java.util.Scanner;
public class Exercise1_4 {
    public static void main(String[] args) {
	   Scanner sc = new Scanner(System.in);
	   int n=sc.nextInt();
           int result=0;
  
int num=n;
int temp;
while(num!=0)
{
  temp=num%10;
  result=result+(temp*temp*temp);
  num=num/10;
}


if(result==n)
{

result=1;
  System.out.print(result);
}
else
{
  result=0;
  System.out.print(result);
}

}
}
           
           
           
