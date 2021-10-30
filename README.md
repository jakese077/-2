#include<stdio.h>
#include<stdlib.h>
void main(void)
{
	int i,i1,i2,i3,i4;
	long double n,n1;
	printf("请输入你的小数和幂次:");
	scanf("%lf %d",&n,&i);
	i1=0,i2=0,i3=0;
	for(i1=1;i1<=i;i1++)
	{
		n*=n;
	}
	printf("%lf",n);
		i2=n;
	if(n<1)
	{
		while(i2>0)
		{
			i2*10;
			i3=i2/1;
			i2=i2-i3;
			i4=i4*10+i3;
		}
		

	}
	if(n>=1)
	{
		i4=i2-(i2/1);
		while(i2>0)
		{
			i2*10;
			i3=i2/1;
			i2=i2-i3;
			i4=i4*10+i3;
		}
	}
	printf(".%d",i4);
	system("pause");

}	
