# assignment-day4
public static void main(String[] args) {
int num = 321;
int sum = 0;
while (num > 0) {
sum = sum + num % 10;
num = num / 10;
}
System.out.println(sum);
}



public class Prime  
{  
public static void main(String[] args)   
    {  
int ct=0,n=0,i=1,j=1;  
while(n<25)  
{  
j=1;  
ct=0;  
while(j<=i)  
{  
if(i%j==0)  
ct++;  
j++;   
}  
if(ct==2)  
{  
System.out.printf("%d ",i);  
n++;  
}  
i++;
}
}
}
