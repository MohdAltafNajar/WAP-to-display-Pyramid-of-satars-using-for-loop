public class Pyramid 
{    
public static void main(String args[])   
{    
//i for rows and j for columns       
int i, j, row = 6;       
//Outer loop for rows  
for (i=0; i<row; i++)   
{  
//inner loop for space      
for (j=row-i; j>1; j--)   
{   
System.out.print(" ");   
}   
//inner loop for columns  
for (j=0; j<=i; j++ )   
{       
System.out.print("* ");   
}   
System.out.println();   
}   
}   
}  # WAP-to-display-Pyramid-of-satars-using-for-loop
