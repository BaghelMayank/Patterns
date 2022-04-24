# Patterns
all patterns
#Pattern 1
1
12
123
1234
internal class Program
    {
        static void Main(string[] args)
        {
            int n = 4;
            for (int i = 1; i<=n; i++)
            {
                for (int j = 1; j<=i; j++)
                {
                    Console.Write(j);
                    
                }
                Console.WriteLine();
            }

            
        }
    }
    
#Pattern 2
 54321
 4321
 321
 21
 1
    internal class Program
    {
        static void Main(string[] args)
        {
            int n = 1;
            for (int i = 5; i>=n; i--)
            {
                for (int j = i; j>=n; j--)
                {
                    Console.Write(j);
                    
                }
                
                Console.WriteLine();
            }

            
        }
    }
    
#Pattern 3
4321
321
21
1
    internal class Program
    {
        static void Main(string[] args)
        {
            int i = 4;
            while(i>=1)
            {
                int j = i;
                while(j>=i)
                {
                    Console.Write(j);
                    j--;
                }
                Console.WriteLine();
                i--;
            }

          }
    }
    
#Pattern 4
a b c d e
a b c d
a b c
a b 
a
 internal class Program
    {
        static void Main(string[] args)
        {

            char alp = 'a';
            int ascii = alp;
            for (int i = 'e'; i >=ascii; i--)
            {
                for (int j = 'a'; j <= i; j++)

                {
                    Console.Write(alp+" ");
                    alp++;
                }
                if (alp >= 'f')
                {
                    alp = 'a';
                }
                else
                {
                    alp = 'a';
                }
            Console.WriteLine();
            }
        }

    }
#Star Pattern
* * * * * *
* * * * *
* * * *
* * *
* *
*
  internal class Program
    {
        static void Main(string[] args)
        {

            int n = 1;
            for (int i = 6; i>=n; i--)
            {
                for (int j = i; j >=n ; j--)

                {
                    Console.Write("*"+" ");
                    
                }
                
            Console.WriteLine();
            }
        }

    }
#Pattern    
   1
  101
 10101
1010101
            int n = 4;//no of rows
            int i, j;
            for (i = 1; i <= 4; i++)
            {
                /* print blank spaces */
                for (j = 1; j <= n - i; j++)
                {
                    Console.Write("  ");
                }
                /* Display number in ascending order upto middle*/
                for (j = 1; j <= i; j++)
                {
                    if (j % 2 == 0)
                        Console.Write('0'+" ");
                    else
                        Console.Write('1' + " ");
                }
                /* Display  number in reverse order after middle */
                for (j = i - 1; j >= 1; j--)
                {

                    if (j % 2 == 0)
                        Console.Write('0' + " ");
                    else
                        Console.Write('1' + " ");

                }
                Console.Write("\n");
            }
        
