# Fibonacci-series-in-C-Program
#include <stdio.h>
void fib(int a, int b, int n);
int main() {
   int a,b,c,n;
   scanf("%d",&n);
   printf("%d %d",a,b);
   fib(a,b,n);
   return 0;}
   void fib(int a,int b,int n){
       int c,i=2;
       while(i<n){
           c=a+b;
           printf("%d",c);
           a=b;
           b=c;
           i++;
           
       }
   }
