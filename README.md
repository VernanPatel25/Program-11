public class Q5
{
   public static void main(int n, int a)
   {
       switch(a)
       {
           case 1:
           
                  for(int i=1;i<=n;i++)
                  {
                      for(int j=1;j<=i;j++)
                      {
                          System.out.print(j);
                      }
                      System.out.println();
                  }
                  break;
                
           case 2:
           
                for(int i=97+n;i>=97;i--)
                  {
                      for(int j=97;j<=i;j++)
                      {
                          System.out.print((char)j);
                      }
                      System.out.println();
                  }
                break;
           default:
                System.out.println("number error");
                break;
    }
