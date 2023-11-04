# EX-2(B)   TRIANGULAR PATTERN

## AIM:
 To write a C program to print the given triangular pattern using loop.

## ALGORITHM:
1.Start the program.
2. Declare the required variables: i,j and n.
3: Read the input value for 'n' using scanf().
4: Set up a nested for loop with the outer loop iterating from i=1 to i<=n and the inner loop
iterating from j=1 to j<=i.
5: Inside the inner loop, print a "#" using printf().
6: After the inner loop completes, print a newline character "\n" to move to the next row.
7: Stop the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
   int n,i;
   scanf("%d",&n);
   for(i=n;i>=1;i--)
   {
      for(int j=1;j<=i;j++)
      printf("#");
      printf("\n");
   }
}
```

## OUTPUT:
![image](https://github.com/Yuvaranithulasingam/EX-02-2b/assets/121418522/8416ffee-5ed3-4efb-81c6-74570a2ee214)

## RESULT:
  Thus , the program is successfully verified.
