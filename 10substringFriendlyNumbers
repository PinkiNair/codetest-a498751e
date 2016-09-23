# 10substringFriendly
10-substring friendly numbers
public static void main(string args[])
{
    try
      {
        long N;
        int sum,r;
        ArrayList 10substringNum=new ArrayList<>();
        Console.Readline("Enter a number");// taking the example N=100 [19, 28, 37, 46, 55, 64, 73, 82, 91]
        N=Console.Readline());
       for(int i=0;i<=N;i++)
       {  
          if(i!=0)
          {
            r=i % 10;
            i=i / 10;
            sum=i + r;
          }
          if(sum==10)
          {
           10substringNum.add(i)
          }
       }
       foreach(num in 10substringNum)
       {
       Console.Writeline("10-substring friendly numbers are :" + num);
       Console.ReadLine();
       }
      }
      catch(Exception ex)
      {
      Console.Writeline(ex);
      }
}
