#include<stdio .h> #include<string .h> void main( )

char jvzi[1000] , danci[20] ,ceshi[20]; printf("输入你的句子: \n");

gets(jvzi) ;

printf("输入你要计数的单词: \n"); gets( danci);

strlwr(jvzi);

strlwr (danci) ;

int x=strlen(jvzi),i,j=0,n=0;

for(i=0;i<x;i++)

if((jvzi[i]<='z'&&jvzi[i]>='a')=0)

for(int k=j,l=0;k<i;k++ ,l++)

ceshi[l]=jvzi[k];>

j=i+1;

if(strcmp( ceshi ,danci)==0)n++;

>

printf("T%d↑%5. n" ,n,danci);
