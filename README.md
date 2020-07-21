# dongda100_1
东北大学C语言编程





#include<stdio.h>
int i,j,k,m[300],n;
int main()
{
 for(i=1,n=0;i<=4;i++)
	 for(j=1;j<=4;j++)
		 for(k=1;k<=4;k++)
		 {
			if(i!=j&&i!=k&&j!=k)
			{
				m[n]=100*i+10*j+k;
				n++;
			}

		 }
		 printf("总共有:%d个\n",n);
		 printf("分别为：\n");

		 for(i=0;i<n;i++)
		 {
			 printf("%d\t",m[i]);
		 
		 }
return 0;
}
